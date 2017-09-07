名字和Email设定  
git config --global user.name "Your Name"  
git config --global user.email "email@example.com"

***

创建仓库

git init

***

添加文件到仓库

git add .

***

提交

git commit -m -

***

配置帐户

ssh-keygen -t rsa -C "youremail@example.com"

把id_rsa.pub文件里的内容复制到GitHub网站里的Key文本框里

***

创建远程仓库

点击 New repository

***

添加远程仓库地址
git remote add origin git@github.com:michaelliao/learngit.git

***

把本地内容推送到远程仓库

git push origin master

***

克隆仓库(从GitHub上下载代码)

git clone git@github.com:michaelliao/gitskills.git
