# It's My Personal Blog (MPBlog) Repo
Based on [docsify](https://docsify.js.org/).

## MPBlog Address
https://xhqing.github.io/mpblog

## Usage
1. set alias in `~/.zshrc` for convenient.
```bash
alias np="python3 np.py"
alias dp="python3 dp.py"
```
remember exe `source ~/.zshrc` after set alias.

2. confirm you are in the root dir of mpblog.
```bash
pwd # /xx/xxx/.../mpblog/
```

3. usage
```bash
# new post, it will generate a your_post_title.md file in `./post` and open it automatically with typora (I use typora).
np your_post_title # np "post_name"

# deploy locally. copy `./post` to `./docs/` and check or modify something automatically.
dp 

# deploy on github just need git push all changes to remote mpblog repo.
```

## GitHub Page Setting
It's very easy.
![img](img/20220128215228.jpg)

## Preview your site
It is recommended to install `docsify-cli` globally, which helps initializing and previewing the website locally.
```bash
npm i docsify-cli -g
```
Run the local server with `docsify serve`. You can preview your site in your browser on `http://localhost:3000`.
```bash
docsify serve docs
```
set alias in `~/.zshrc` for convenient
```bash
alias ds="docsify serve docs"
```
then
```bash
source ~/.zshrc
```

## LICENSE
MIT
