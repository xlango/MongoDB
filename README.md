# MongoDB
mongoDB开源的NoSQL数据库 <br>
1.LAMP互联网开发架构(Linux、Apache、MySQL、PHP) <br>
2.MongoDB的概念：MongoDB、mongo、索引、集合、复制集、分片、数据均衡 <br>
3.学会MongoDB的搭建<br>
  ![Image text](https://github.com/xx132917/MongoDB/blob/master/img/modbbuild.png) <br><br>
4.熟悉MongoDB的使用 <br>
   (1)最基本的文档的读写更新删除  <br>
   (2)各种不同类型的索引的创建与使用 <br>
   (3)复杂的聚合查询 <br>
   (4)对数据集合进行分片，在不同分片间维持数据均衡 <br>
   (5)数据备份与恢复 <br>
   (6)数据迁移 <br>
5.简单运维 <br>
   (1)部署MongoDB集群 <br>
   (2)处理多种常见的故障 <br>
      --单节点失效，如何恢复工作 <br>
	  --数据库以外被杀死如何进行数据恢复 <br>
	  --数据库发生拒绝服务时如何排查原因 <br>
	  --数据库磁盘快满时如何处理 <br>
6.Window安装MongoDB <br>
    (1)下载解压：http://www.mongodb.org/downloads <br>
	(2)创建安装db文件夹:例如d:\mongodb\data\db   日志文件：例如d:\mongodb\data\log\MongoDB.log  <br>
	(3)进入bin目录cmd执行：mongod -dbpath "d:\mongodb\data\db" 启动，MongoDB默认监听端口27017  <br>
	(4)测试连接：bin目录下输入mongo或mongo.exe进入测试，exit或者ctrl+C退出  <br>
	(5)当mongod.exe被关闭时，mongo.exe 就无法连接到数据库了，因此每次想使用mongodb数据库都要开启mongod.exe程序，所以比较麻烦，此时我们可以将MongoDB安装为windows服务<br>
	   cmd在bin目录下执行：mongod --dbpath "d:\mongodb\data\db" --logpath "d:\mongodb\data\log\MongoDB.log" --install --serviceName "MongoDB" <br>
	   启动服务：NET START MongoDB  <br>
	   关闭服务：NET stop MongoDB  <br>
	   删除进程：mongod --dbpath "d:\mongodb\data\db" --logpath "d:\mongodb\data\log\MongoDB.log" --remove --serviceName "MongoDB" <br>
	(6)参考：https://www.cnblogs.com/lecaf/archive/2013/08/23/mongodb.html <br>
	(7)可视化工具的使用参考：https://jingyan.baidu.com/article/8ebacdf0752d0149f65cd521.html  <br>




  
