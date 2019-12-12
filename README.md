# layui-source-study
GIT工作流程：
	1. git init
	2. git remote add origin XXXXX.git
	3. 使用git branch 查看本地是否具有dev分支
                4. 如果没有 git fetch origin dev

	5》git checkout -b dev origin/dev在本地创建分支dev并切换到该分支 
		注意： 第五步，在没有分支，不需要建立dev分支，
		不要做，否则，会将 仓库文件名称  clone 下来
	
	6》git pull origin dev就可以把gitLab上dev分支上的内容都拉取到本地了
	7.  git push --set-upstream origin master 建立push 的地址；
	8.  git add .
	     git commit -m ""
	    git push