git config --global user.name "aaa"
git config --global user.email ""

git checkout -- fileName
	fileName文件修改了，未放入暂存区，把文件在工作区的修改全部撤销。

git reset head fileName
	fileName文件修改了，已放入暂存区，把暂存区的修改撤销掉,重新放回工作区。
	
git checkout -b dev (或者git switch -c dev)
	git checkout 命令加上 -b 表示创建并切换分支。
	相当于：git branch dev
			git checkout dev

git merge dev
	git merge 命令是将dev分支合并当前的分支。

git branch -d dev
	删除Dev分支。

