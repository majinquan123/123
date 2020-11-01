git

1、在一个文件夹中新建文件   mkdir a

2、显示当前目录  pwd

3、显示当前文件  ll ls

4、清屏  ctrl+l

5、全局配置git 邮箱  git config --global user.email 'xxx'    不需要全局的删除 --global

6、全局配置git 用户名 git config --global user.name 'xxx'

7、初始化本地仓库 建立暂存区 git init

8、查看创建的git仓库 ls -a

9、克隆一个项目  不用git init 不要在已经有git文件夹里面克隆  直接 git clone 

10、rm -rf * 删除所有目录

11、查看本地状态 git status

12、新建一个空白文件  touch a.php

13、从仓库里面删除东西  git rm a.php 

​		如果想将这个文件在 本地保留 git rm --cached a.php  然后跳过 git add 使用git commit -m ''

14、版本库中修改资料名称

