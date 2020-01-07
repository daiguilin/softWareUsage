## SVN使用教程

##### 1，首次拉去代码

准备工作：新建存放代码目录，拉取代码的SVN地址，以及SVN账号和密码

桌面空白处右键选择checkout，出现如下截图，填入SVN代码地址和存放目录，点击OK，首次会让输入账号和密码，输入完成按引导操作即可拉取代码

<img src="C:\Users\dgl\AppData\Roaming\Typora\typora-user-images\image-20191211172318966.png" alt="image-20191211172318966" style="zoom: 80%;" />

##### 2，代码开发流程

1. 每次开发之前，工程目录下，右键-->SVN Update,拉取代码
2. 开发完成后。再次执行上一步操作，拉去我们开发过程中别人提交的代码
3. 遇到文件删除的情况，点击文件--->右键-->SVN-->delete,(此操作实现了从服务器上删除，不能只从本地删除)
4. 出现冲突解决冲突：编辑器内手动解决冲突--> 选中冲突文件右键-->SVN-resolved （告诉SVN已解决完冲突）
5. SVN Commit

参考链接： https://blog.csdn.net/Rundy_Deng/article/details/80338093 