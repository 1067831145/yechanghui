# 我的文档
## 安装gitbook 
全局安装
npm install gitbook-cli -g

初始化
gitbook init
生成README.md和SUMMARY.md

启动
gitbook serve

同步到github上
    先初始化git
    git init
    执行之后会有.git文件，通常会被隐藏，可以执行ls -la查看当前存在的所有文件
    github上新建项目，复制项目地址
    git remote add origin https://github.com/1067831145/yechanghui.git
    git add .
    git commit -m "xx"
    git push

    提交之后，只是把源文件提交到github上
    
再建立分支，如test分支
git branch test

切换到test分支
git checkout test

把_book里面的文件搬出到根目录（覆盖即可）
再次执行 
    git add .
    git commit -m "xx"
    git push
此时github上已经有两个分支

分配线上网址
可以在setting上（最右选项）上配置，
私人的要交钱才有，公开的把Source列下的none配置test分支的内容，即可生成

要将私人的变成公开的：
setting最下边的Danger Zone-》Change repository visibility可以改变，在填写分支结构时候注意不要有空格号，复制也会有空格，要去掉，不然点击不了I understand, change repository visibility.




