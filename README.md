
## git 操作命令

用于记录一些git 的常用命令

git忽略掉一些已经提交到远程仓库的文件 例如.idea/workspace.xml 执行下面命令后在.gitignore文件里面添加上.idea/workspace.xml文件

> git rm -r --cached .ide

git 比较两个版本之间的差异文件并且打包

> git diff f92be38 bf0505c --name-only | xargs tar -zcvf /home/download/update.tar.gz

git合并

> git --no-f -m "xxx" 分支名
