1) cd到文件工作目录下

使用命令行或Git Bash，输入下面命令：先进入到工作目录下，再输入git init（初始化一个仓库）

2）将所有文件添加到仓库
使用命令行或Git Bash，输入下面命令：git add .(.是所有文件，可以git add Classes 表示添加Classes文件)

3）提交
使用命令行或Git Bash，输入下面命令：git commit -m “CommitInfo”

4）添加源到GitHub
git remote add origin git@github.com:YourName/YourRepositroy.git

5）上传源到GitHub
git push -u origin master
