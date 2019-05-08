# Git 总结

一. git本地仓库与远程仓库建立关系的两种方法：

1. git clone git@github.com:Hibanna/JavaSE.git 

   > 这种方法会自动将远程仓库下载到本地并建立关系，创建master分支并将本地master与远程仓库master相关联。

2. git init 初始化本地仓库 并建立本地master分支

   git remote add origin git@github.com:Hibanna/JavaSE.git 将本地仓库与远程仓库建立关系

   git push -u origin master 将本地master与远程仓库master相关联。
[^1]:  本地master与远程仓库master相关联 可以简化push 命令 例如：git push 等价于 git push origin master


