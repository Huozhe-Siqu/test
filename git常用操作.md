#常用操作
##git clone
从git服务器拉取代码

##git config
配置开发者用户名和邮箱,每次代码提交的时候都会生成一条提交记录，其中会包括当前配置的用户名和邮箱
git config user.name xxx
git config user.email xxx

##git branch
创建，重命名，查看，删除项目分支，通过git做项目开发时，一般都是在开发分支中进行，开发完成后合并到主干
###git btanch daily/0.0.0
创建一个名为daily/0.0.0的日常开发分支，分支名只要包含特殊字符即可
###git branch  -m daily/0.0.0 daily/0.0.1
可以为新建的分支重命名，重命名分支名为daily/0.0.1
###git branch
查看当前的分子列表

