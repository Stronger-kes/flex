## github上watch,star,fork的含义

    watch:关注，如果代码有变化会及时通知到你的邮箱
    star:收藏
    frok:拷贝其他用户项目到本地仓库(通常不建议使用，除非你想给其他用户贡献代码)

## 如何忽略本地不想提交的目录或(文件)
    
    .gitignore
## 本地文件的历史回退

    所谓版本：即用 git commit 一次就是一个版本

    放弃工作区的修改： git checkout -- 要放弃修改的文件名 可以跟多个文件

    放弃暂存修改：

    回退分支版本： git reset --hard commit_id


## 分支管理

    master:通常用于发布产品的分支
    dev：开发分支
    bug：修复bug的分支
    deater：添加新功能的分支

    分支常用的命令：
        1、查看分支： git branch
        2、创建分支： git branch 分支名
        3、切换分支： git chechout 要切换换的分支名

## tab管理