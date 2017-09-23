mmall_learning
second
连接到远程仓库，并且提交代码
 git add *
 git commit -m "这里是备注，那个文件被更改了就会咋github上显示"
 git remote add origin https://github.com/DoubleWeiWei/mmall.git
 git push -u origin master

 #查看分支
 git branch
 #查看远程分支
 git branch -r
 #查看所有分支
 git branch -a

 #提交分支数据到远程服务器：
 git push origin <local_branch_name>:<remote_branch_name>