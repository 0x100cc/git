Git is a distributed version control system.
Git is free software distributed under the GPL.

Git 命令大全
mkdir ...
cd ....
git init 把这个目录变成git可以管理的仓库
git add readme.txt
git commit -m "wrote a readme file"
git status
git diff readme.txt 查看变化
git log 查看提交过的日志
git reset --hard HEAD^（id) 退回到上一个版本
git reflog 查看命令历史
git checkout --file 可以丢弃在工作区的修改
如果已经add了，用 git reset HEAD file 把暂存区的修改撤销掉，然后 git checkout --file
git rm file 删除一个文件，想恢复，就得git checkout --file（会从版本库恢复最新的版本）,想彻底删除，就再提交一次 git commit -m ""
