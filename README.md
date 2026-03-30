# Git
## Question 1
- 已将此目录初始化为Git项目仓库。
## Question 2
- 已将README.md文件添加到Git项目仓库中。
## Question 3
- 未作改变时当前仓库状态为On branch master nothing to commit, working tree clean
- 改变后查询当前仓库状态，会提示目录仓库下未提交的更改和未跟踪的文件，并显示no changes added to commit (use "git add" and/or "git commit -a")
- 新增的信息说明Git可以检查已跟踪文件是否更改以及仓库目录下新加入的未跟踪文件。
## Question5
- HelloWorld.java文件的功能为输出既定次数的"Hello World！"字符串。
- 不同文件修改的分次提交依赖的是Git的“暂存区”功能，提交时只会提交暂存区中的文件更改，而不会提交工作区中未添加到暂存区的更改。
## Question 6
- 当前分支名称为master。
- 已修改HelloWorld.java文件并在newbranch分支上提交了更改。
- 已修改README.md文件并在master分支上提交了更改。
- 已将newbranch分支合并到master分支上,合并时自动提交。
## Question 7
- 新建一个分支，修改README.md文件中的某一行提交，然后切换回原来的分支，修改README.md文件中的同 一行提交。这时将新分支合并到当前分支后，git 提示分支修改内容冲突，文件中同一位置出现了分别在两个分支中提交的不同修改内容，表示git 无法自动合并，需要用户手动解决冲突。
- <<<<<<<后表示当前分支下的修改内容，=======表示上下两端的分割线，分割线后>>>>>>>前表示合并进来的分支下提交的修改内容，同时表示冲突标记结束。用户需要根据实际情况选择保留哪个分支的修改内容，或者进行修改后保留两者的内容，解决冲突后再提交合并。
## Question 8
- 可视化合并历史[如图](imgs/合并历史可视化.png)
## Question 9
- 成功建立本地和远程Github仓库的连接并将本地仓库推送至远程仓库。[如图](imgs/远程仓库.png)
## Question 10
- 成功下载刚刚推送的仓库[如图](imgs/下载远程仓库.png)
- 