# git和github
git用于本地仓库的维护
GitHub是远程仓库
利用git实现本地和远程的互传
这两者都是用来做版本控制的，同时方便多人项目开发，GitHub还提供用户间丰富的开源资源共享

# 从小白到入门
1. 首先注册GitHub账户，sign up
2. 注册完毕后可以登录了，同时为了方便浏览，可以先去网上寻找方法解决国内访问过慢问题
3. 安装git
4. 通过ssh密钥绑定git和GitHub
5. 在GitHub中new一个public远程库
6. 在本地创建空文件夹，点进去后右键git bash here，打开git命令行
7. 输入git init可以将文件夹初始化为一个本地库，同时默认带一个master分支
8. 之后可以尝试练习在本地进行创建文件，修改文件，删除文件以及commit操作
9. 同时也可以练习各种git命令
10. 之后为了获取远程库连接，需要利用之前创建的远程库的ssh，添加远程仓库
11. 添加后可以进行对远程仓库的各种git命令练习，例如查看等
12. 尤其练习一下本地仓库和远程仓库的pull push操作【注意，最好先pull再push，这是为了防止远程仓库有更新】 
13. 之后可以把本地库的文件夹删除，然后打开远程库点击code复制ssh，然后使用clone指令copy远程仓库到本地，这个本地库无需init，之后再练习版本控制等操作