Git Pycharm 日常使用

** 旨在记录git的日常使用指令

checkout : 切换不同分支

add : 一般pycharm自动提示做add操作 ->加入到缓存区

commit : 将暂存区文件提交到分支（本地仓库）

push ： 将本地仓库同步到远程仓库 master -> origin/master

merge : 不同分支间的合并 例如在dev分支中有新的修改，需要checkout到master做merge

实际操作中，在提交代码之前，首先update project，再commit - push.

日常提交代码步骤：
按ctrl+T 下拉此branch最新代码 =svn的update

按ctrl+K  提交一个commit（此时没有提交到远程库，如果你熟悉git指令此处为git add +git commit）

确认代码开发OK后按 ctrl +shift +k   push本机代码到gitlab 服务器

备注：日常简单更改可直接在dev分支进行，功能性较大开发建议新开功能分支，待功能验证OK后merge到dev分支，

我会在周三打包前把可用的dev分支merge到master，请不要直接提交到master分支。

