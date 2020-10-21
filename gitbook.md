### gitbook+github搭建文档网站

##### 一. 安装gitbook命令行工具
`npm install -g gitbook-cli`

##### 二. github上新建项目my-book

##### 三. 关联github项目和gitbook
1. clone项目my-book到本地
2. 初始化gitbook
```
cd my-book
gitbook init
```
3. 本地启动
`gitbook serve`

##### 四. 推送到github，访问线上文档
```
git add .
git commit -m 'message'
git push -u origin master
git subtree push --prefix=_book origin gh-pages
```
完成以上四步，就可以推送到线上了，然后你可以通过以下链接访问到自己的项目：

https://<你的用户名称>.github.io/<你的项目名称>/
