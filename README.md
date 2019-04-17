"
本地资料库到远程资料库：
先激活虚拟环境
git init：初始化本地资料库
touch README.md：创建readme以便对项目的描述
git add -A:监控工作状态树
git commit -m "xxx":项目添加到本地资料库，xxx为描述，每次都要替换描述
git remote add origin http//xxx.git:你的github远程资料库链接
git push origin master:项目推送到到github

第一次要以上的操作，后面要是推送到远程资料库只需
git add -A
git commit -am "message"
git push origin master
"