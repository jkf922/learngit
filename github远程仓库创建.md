github远程仓库创建：

- http
  1. github建立新的仓库repository
  2. 公开仓库，public，private只能自己看，但要交钱
  3. readme可要可不要
  4. 本地仓库文件夹下git init，初始化，生成了一个.git目录，用来跟踪管理版本库的，被隐藏了，ls -ah查看
  5. 与仓库保持一致，git config --global user.name "用户姓名"
  6. git config --global user.email "用户邮箱"
  7. git remote add origin （http链接）
  8. 拉取远程代码git pull origin master
  9. 添加要上传的文件git add .
  10. 提交并说明git commit -m "firstcommit"
  11. 把代码推到远程仓库git push -u origin master
  12. git log查看版本信息，git log --stat查看提交详细信息
  13. git status查看分支信息



- 