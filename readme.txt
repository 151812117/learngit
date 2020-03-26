1.git config --global user.email "151812117@qq.com"
2.git config --global user.name "rc"
3.cd c:\cr
   mkdir repo
   cd repo
4.git add readme.txt
5.git commit -m "create a new readme"
   返回：c:\CR\repo>git commit -m "create a new readme"
             [master (root-commit) f3982d9] create a new readme
             1 file changed, 1 insertion(+)
             create mode 100644 readme.txt
6.git status:查看工作区的状态，告诉你有文件被修改过；用git diff可以查看修改内容
7.版本回退：HEAD指向的版本就是当前版本，HEAD~n表示当前版本的前n个版本，因此，Git允许我们在版本的历史之间穿梭，使用命令git reset --hard commit_id
   用git log可以查看提交历史，以便确定要回退到哪个版本。
   用git reflog查看命令历史，以便确定要回到未来的哪个版本。
8.conflict