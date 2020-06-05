----------
6/5/2020 2:05:35 PM 
----------
1、在github上新建一个仓库，创建时有一个https地址，记录此地址，后面用
2、打开git bash，转到你所要上传的文件夹目录下，并输入git init
3、将项目添加到仓库中去：git add .，如果添加某个文件，可以使用git add xxx
4、将添加的文件提交到仓库：git commit -m "--注释--"
5、将仓库关联到github：git remote add origin https://xxxx，https为刚才github上创建仓6、库的地址
7、把文件推送到github仓库：git push -u origin master，下次推送时，可以把-u去掉

如果你有修改过的文件
1、git stash
2、git pull --rebase master（每次push之前最好这样做一次）把github上面的文件拉到本地再上传
git push ....