1. first day
2. xiaochen xiugai
3. fourth day	
4. third day

	1.git 
		git clone xxxx  	从服务器下载git仓库
		git status      	显示内容变化
		git add xxx     	添加文件到本地仓库
		git add .       	添加所有文件到本地仓库
		git commit -m "first commit" 确认提交文件到本地库 -m "xxx", 添加log
		git branch xxx   	创建xxx分支
		git checkout xxx 	从当前分支切换到xxx分支
		git diff xxx 		查看与之前版本的不同
		git log			查看大概log信息
		git add -u 		添加修改后的文件到本地仓库
		git log -p 		查看详细信息
		git merge xxx		把xxx分支上的内容合并到当前分支
		git reset xxx 		仓库回退到xxx这个版本
		git clean -xdf		删除跟代码仓库没有关系的文件
		git init 		初始化git仓库