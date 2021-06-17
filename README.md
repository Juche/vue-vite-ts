# vue-vite-ts

> Create a project base on vue3.x vite &amp; typescript ...

## Steps

- 初始化

```sh
# init project(这个过程可以关联仓库项目地址)
yarn init
# verified github account and add remote repository
# 设置提交代码时的用户信息：
git config user.name "Juche"
git config user.email azhucheng1@qq.com
# commit to repository
git add package.json
git commit -m 'package.json'
git push origin master

# 撤销已 push 到仓库的提交
git reset --soft 7ac94fc052a82693341972ce234e18d3ecf8b731
# 必须添加参数force进行强制提交，否则会提交失败
git push origin  master --force
```

- 建立项目结构

```sh
├─dist
├─node_modules
├─public
├─src
│  ├─assets
│  ├─componets
│  ├─router
│  ├─store
│  └─views
└─test
```

- 逐步安装依赖和创建编写对应的文件

```sh
yarn add vite --dev

# 接下来创建 index.html/main.js 等文件
# 一个最基本的可运行 web 项目就搭建好了
# 通过 vite 启动静态服务(默认 3000 端口)
npx vite
```
