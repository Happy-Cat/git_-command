git clone git@github.com:Happy-Cat/git_command.git                 //克隆库
git checkout -b test                                               //创建本地分支并切换
git checkout                                                       //切换分支
git branch -a                                                      //查看远程分支
git branch                                                         //查看本地分支
git branch test                                                    //创建分支
git commit -m '第一次'                                             //添加注释
git push git@github.com:Happy-Cat/git_command.git                  //提交

git add . //他会监控工作区的状态树，使用它会把工作时的所有变化提交到暂存区，包括文件内容修改(modified)以及新文件(new)，但不包括被删除的文件。
git add -u //他仅监控已经被add的文件（即tracked file），他会将被修改的文件提交到暂存区。add -u 不会提交新文件（untracked file）。（git add --update的缩写）
git add -A //是上面两个功能的合集（git add --all的缩写