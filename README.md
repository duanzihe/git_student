# git_student
此仓库用于本人对github的使用学习  
首先我将练习最基本的使用流程，以下是如何使用 Git 并通过 GitHub 仓库进行常见操作的基本指南。  
这将包括克隆（拉取）仓库、修改文件、增加文件、提交更改、以及创建与合并分支的步骤。  
首先检查代理服务器，利用git config修改和自己电脑匹配的ip端口，再利用git clone拉取仓库  （或者用git init新建一个空仓库）


![image](https://github.com/duanzihe/git_student/assets/106713739/089fbe96-7935-4ce6-b1e5-f5da63a30d3d)  

  接着，创建一个样例文件，利用git add 将文件保存到暂存区，再利用git commit -m “提交信息”将在暂存区中的文件提交到本地仓库（注意，在这一步之前要登录一下github，如下图）  
  ![image](https://github.com/duanzihe/git_student/assets/106713739/a881612a-a893-4cff-af74-5a5334907f88)  

现在的话，还需要用命令
$ git remote set-url origin https://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@github.com/duanzihe/rust_study.git


加上令牌，如下图
![375fb34b9f73b3e363ca0f9df351584e](https://github.com/user-attachments/assets/0177578a-38f2-413e-b0f0-98e412810a60)

  在提交到本地仓库后，再利用git push将本地仓库的更改推送到远程仓库。
  为什么要分暂存区，本地仓库，远程仓库三步？


