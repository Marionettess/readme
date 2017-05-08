# GitHub问题集（2）
1. 个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？  
	new repository, import repository, 	new gist, 			new organization.
	建立新仓库,		导入仓库,			数据的粘贴和引用,	创建新的组织.

2.	如何能将仓库中的html文件直接解析成页面？  
	将链接粘贴进: http://htmlpreview.github.com/

3.	如何删除仓库  
	在该库的settings里的底部有删除.

4.	Bash是什么操作系统的命令  
	Unix家族的.

5.	Pwd是什么命令  
	查看当前目录.

6.	Cd是什么命令  
	切换当前目录.

7.	Echo是什么命令  
	响应, 亦可用来创建文本文件.

8.	配置git用户名的命令  
	git config --global user.name 'a'

9.	配置邮箱的命令  
	git config --global user.email "15732115701@163.com"

10.	命令行换行方式  
	字符\

11.	命令行终结方式  
	Ctrl + c, Ctrl + d(2者有所不同, 不在这细说)

12.	使用命令行比GUI方式有何优势  
	根本上: 一些功能在GUI中是无法实现的, 
		其次:	命令行的效率要高于GUI.

13.	提交到本地仓库时为什么有暂存区  
	作为缓存, 提高了效率,
	细化一次提交, 划分版本, 多一层确认保障.

14.	新建代码仓库的命令  
	github-create REPO_NAME

15.	git clone [url] 这个命令的作用是  
    将url对应的仓库拷贝到本机目录下.

16.	添加指定文件到暂存区的命令  
	git add NAME_OF_FILE.

17.	删除工作区文件，并且将这次删除放入暂存区的命令  
	git rm [file1] [file2] ...

18.	改名文件，并且将这个改名文件放入暂存区的命令  
	git mv [file-original] [file-renamed]

19.	提交暂存区到仓库的命令  
	git commit -m "XXXX", 
	或 git commit 后进入记事本输入相应的"XXXX" 

20.	直接从工作区提交到仓库的命令  
	git add NAME_OF_FILE | git commit -m "SOME_MESSAGE"

21.	显示变更信息的命令
	git status

22.	查看历史信息的命令
	git log --follow [file], git whatchanged [file]

23.	Commit的意义是
	提交.

24.	Pull的意义是
	拉取文件.

25.	Push的意义是
	上推文件.