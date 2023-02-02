# github使用教程

## 一 首次上传此文件夹
### （一） github与git连接--本地Git仓库
1. 本地文件夹
    * 右键-Git Bash-
    * 输入“git init”初始化成一个Git可管理的仓库

2. 将本地文件add到Git仓库上
    * git add .  //. 表示添加该目录下所有文件
    * git status //用来查看仓库状态

3. 把项目提交到仓库
    * git commit -m " 注释 “”

###  （二） github和git连接--远程连接
1. 创建SSH key（只用一次就行了）
2. 在github上新建仓库
3. 关联远程仓库
    * git remote add origin https://github.com/XXX（自己仓库）
4. 本地内容上传
    * git push (-u) origin main   //初次上传必须加上-u

## 二 后续更新上传
1. 将本地文件add到Git仓库上
    * git add .  //. 表示添加该目录下所有文件
2. 把项目提交到仓库
    * git commit -m " 注释 “”
3. 本地内容上传
    * git push (-u) origin main   //初次上传必须加上-u