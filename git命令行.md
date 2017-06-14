### git命令行
#### 1.个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？

New repository   
Import repository 导入库
New gist         导入代码片段
New organization 新建组织
#### 2.如何能将仓库中的html文件直接解析成页面？

找到GitHub Pages板块下面的 launch autommatic page generator，往下翻找到绿色按钮continue to layouts，接下来找一个自己喜欢的主题，再点击绿色按钮publish page，就成了下面这样子。中间的那个网址就是接下来可以访问到你网页的地址了。
#### 3.如何删除仓库：

1.settings
2.delete this repository
3.i understand the consequences,delete this repository
#### 4.Bash是什么操作系统的命令：

linux
#### 5.Pwd是什么命令：

用于打印当前工作目录的工作路径
#### 6.Cd是什么命令：

改变当前目录

#### cp是什么命令 ：copy
#### 7.Echo是什么命令：

打印信息
#### 8.配置git用户名的命令

git config --global user.name "youname"
#### 9.配置邮箱的命令：

git config --global user.email "youeamil@email.com"
#### 10.命令行换行方式：

斜杠
#### 11.命令行终结方式：

（ctrl+z挂起当前进程如果需要恢复到前台输入fg,恢复到后台输入bgctrl+c）
ctrl+c
#### 12.使用命令行比GUI方式有何优势：

1.GUI可视化的图形界面，不用记命令
2.命令行能够批量处理仓库内容
#### 13.提交到本地仓库时为什么有暂存区：

工作区的代码入库需经过暂存区，选择性的提交，分开多个版本，可以选择一次提交成几个版本
#### 14.新建代码仓库的命令：

git init
#### 15.git clone [url] 这个命令的作用是：

下载一个项目和他的整个历史
#### 16.添加指定文件到暂存区的命令
：
git add [file1] [file2]
#### 17.删除工作区文件，并且将这次删除放入暂存区的命令：

git rm [file1] [file2]
#### 18.改名文件，并且将这个改名文件放入暂存区的命令：

git mv [file-origin] [file-renamed]
#### 19.提交暂存区到仓库的命令：

git commit -m [message]
#### 20.直接从工作区提交到仓库的命令：

git commit -a -m [message]
#### 21.显示变更信息的命令：

git status
#### 22.查看历史信息的命令：

git log
#### 23.Commit的意义是：

将暂存区或工作区代码提交到仓库
#### 24.Pull的意义是：

将远程仓库的提交拉下到本地
取回远程主机某个分支的更新，再与本地的指定分支合并
#### 25.Push的意义是：

将本地的提交推送到远程仓库
将本地分支的更新，推送到远程主机

