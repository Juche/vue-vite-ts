# vue-vite-ts

> Create a project base on vue3.x vite &amp; typescript ...

## Steps

```bash
# init project
yarn init
# verified github account and add remote repository
设置提交代码时的用户信息：
$ git config user.name "Juche"
$ git config user.email azhucheng1@qq.com
# commit to repository
git add package.json
git commit -m 'package.json'
git push origin main

# 撤销已 push 到仓库的提交
# 查看提交记录
git log
# 最后一串 hash 是对应提交记录
git reset --soft 7ac94fc052a82693341972ce234e18d3ecf8b731
# 必须添加参数force进行强制提交，否则会提交失败
git push origin  main --force
```
