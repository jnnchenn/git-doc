git版本管理示例

## 创建远程仓库
    gitHub / your repository 新建目标仓库，命名 “git-test”，SSH地址“git@github.com:jnnchenn/git-test2.git”

## 初始化本地项目
    # 创建README.md
    $ echo "# css-test" >> README.md 或者 touch README.md 
    # 在当前目录新建一个Git代码库
    $ git init 
    # 从工作区添加指定文件到暂存区
    $ git add README.md 
    # 从暂存区提交到到本地仓库
    $ git commit -m "git-test first commit" 
    # 添加远程仓库地址
    $ git remote add origin git@github.com:jnnchenn/git-test.git 
    # 推送文件到远程仓库master分支

## 修改项目
    git pull origin master
    // dosomething ...
    git add .
    git status 
    git commit -m "first update"
    git push origin master

## 拉取项目
    git clone git@github.com:jnnchenn/git-test.git
