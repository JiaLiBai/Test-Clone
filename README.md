# Test-Clone
在github上新建项目 new repositories 通过命令行创刊一个新的仓库


1、echo "# project file" >> README.md  这句代码不懂 但结果是在project file目录下新建一个README.md文件
2、git init  初始化本地仓库
3、git add .
4、git commit -m '提交文案 这里新建了一个readme文件'
5、git branch -M master 当前分支重命名为master
6、git remote add origin github项目地址
7、git push -u origin master  第一次对空远程仓库提交时需要带上 -u 命令