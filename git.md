#Git使用#

###工作区（Working Directory）###
本地电脑里能看到的目录，比如我的mygitrepo文件夹就是一个工作区：
###版本库（Repository）###
工作区有一个隐藏目录.git，就是Git的版本库。

##初始化本地库##
    mkdir reponame
    cd reponame
    git init

##文件增加提交##
    git add myfile.txt
    git commit -m "add file"

##远程仓库##
*  添加远程仓库  
   `git remote add origin git@github.com:username/reponame.git`  
   远程库的名字就是origin，这是Git默认的叫法，也可以改成别的，但是origin这个名字一看就知道是远程库。

*  推送本地内容到远程库  
   `git push -u origin master`  
   把本地库的内容推送到远端，用git push命令，实际上是把当前分支master推送到远程。

*  远程仓库clone  
   `git clone https://github.com/plusjade/jekyll-bootstrap.git`
   
##删除文件##
    rm myfile.txt
    git rm myfile.txt
	
##恢复删除的文件##
    git checkout -- recoverfilename  
    **只能恢复rm命令删除的文件，git rm命令执行以后，文件无法恢复**



