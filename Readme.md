学习使用Git命令进行操作

之后的Git命令都会放在当前文件

** git 基本操作

  git init
  创建新的Git仓库

  git clone git@github.com:ellis-s/Demo.git
  检出远端服务器上的仓库

  git remote add origin git@github.com:ellis-s/Demo.git
  将当前仓库链接到某个远程服务器

  git add Readme.md
  把要提交的文件添加到暂存区

  git commit -m "first commit"
  提价更改，就是把暂存区的所有内容提交到当前分支

  git push origin master 
  把提价的内容推送到远程的master分支

**分支：

  git checkout -b feature_x
  创建一个叫做“feature_x”的分支， 并且切换过去

  git checkout master
  切换回主分支

  git branch -d feature_x
  删除feature_x分支

  git push origin <branch>  git push origin feature_x
  把自己新建的分支推送到远端仓库，否则他人不可看到该分支

**更新与合并：






参考：Git-简明指南  http://rogerdudler.github.io/git-guide/index.zh.html 