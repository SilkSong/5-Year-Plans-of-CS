# 2024.12

2024.12.11

* 重新梳理 Shell 脚本输出重定向的知识, 了解了 Shell 文件描述符以及 2>&1 的用法
* git 创建分支后，第一次推送远程分支时使用 -u 参数来建立本地分支与远程分支的追踪关系，后续直接使用 git pull 和 git push 而不用显式指定远程分支名字: 
   `git push -u origin new-branch`   使用 `git branch -vv` 查看分支追踪装填