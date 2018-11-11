


#####
    1.git push遇到fatal: refusing to merge unrelated histories？
    
    强制解决方法：把2段不相干的分支进行强行合并。
        git pull origin master --allow-unrelated-histories
    
    2.本地项目Push到远端？
        git init
        git add .
        git commit -m "xxx"
        git remote add push origin "https://github.com/xxx"
        git push -u origin master
    
    
    
