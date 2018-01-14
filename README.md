This is a big project

初次配置创建用户邮箱
> git config --global user.name "Wang_Ben"
> git config --global user.email "184125908@qq.com"



创建git工作空间 在本地项目目录下 git init	（会出现.git文件夹）

报存到暂存空间    在文件目录  git add 文件名	（不会有任何提示）

提交到git仓库     在文件目录 git commit -m "提交注释" （出现提示提交成功）




--查看状态（工作空间文件的状态）   git status

	两种情况：1，文件没变动
			  2，改动
			  		解决办法两个：1，文件重新添加到暂存区域    git add 
			  							--提交到git仓库
			  							--不提交到仓库，改工作空间的文件状态依然是改动状态，，，，
			  					  2，暂存区域覆盖工作空间的文件   git checkout -- 文件名

--将最近一次提交的文件恢复到暂存区域（将暂存区域还原到上一版本）
	不指定文件名将恢复所有
	 git reset HEAD 文件名


--查看日志 git log
	记录按日期从近到远


