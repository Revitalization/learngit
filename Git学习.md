# Git学习

## 一、Git简介

+ 初始化Git仓库：***git init***
+ 添加文件到Git仓库：
  + 添加文件到暂存区：***git add <file>***
  + 提交文件到仓库：***git commit -m <message>***

## 二、时光穿梭机

+ 查看执行结果，查看仓库状态：***git status***
+ 查看具体的修改：***git diff <file>***

### 1. 版本回退

+ 查看提交历史，以便回退到指定版本：***git log***
+ 查看命令历史，重新回到现在版本：***girt relog***

+ HEAD指向的为当前版本，在版本的历史之间穿梭：***git reset --hard commit_id***

