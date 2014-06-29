[Git 日志]
$ git log --pretty=oneline
$ git log
输入 q 退出日志


[版本回退上个版本]
$ git reset --hard HEAD^


[命令记录]
$ git reflog


[Git 分支]
$ git push origin master 推送分支
$ git checkout -b BranchName 创建+切换分支
$ git merge BranchName 合并某分支到当前分支
$ git branch 不带参数：列出本地已经存在的分支，并且在当前分支的前面加“*”号标记
$ git branch -r 列出远程分支
$ git branch -a 列出本地和远程分支
$ git branch BranchName 创建新的 本地 Branch
$ git branch -d Branchname 删除branch
$ git branch -d -r Branchname 删除远程branch（例git branch -d -r origin/aa)
$ git push <remote repository> <local branch> 把本地branch 推送到远程服务器
$ git checkout name 切换分支
$ git remote -v 要查看远程库的信息

[移动或重命名文件]
$ git mv old-filename new-filename


[从工作目录和 Git 代码索引中删除文件]
$ git rm filename