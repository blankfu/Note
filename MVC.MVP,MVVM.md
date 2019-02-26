### MVC  
mvc是最常见的软架构之一，mvc模式的意思是软件可以分为三个部分。  
* 视图（view）：软件的用户界面  
* 控制器（controller）：业务逻辑  
* 模型（model）：数据保存  

各个部分通信方式如下：  
- view传送指令到controller  
- controller完成业务逻辑后要求model改变状态（存值操作）  
- model将新的数据大送到view，用户得到反馈  
所有的通信都是单向的  

### MVP  
mvp模式将controller改名为presenter，同时改变了通信方向  
view双向箭头符号presenter双向箭头符号model  
- 各部分之间的通信都是双向的
- view与model不发生联系  
- view不部署任何业务逻辑，被称为被动式图（），不具有任何主动性，而presenter里面包含很多业务逻辑  

### MVVM  
mvvm将presenter改名为viewmodel，基本上和mvp模式一致  


原文地址：[MVC，MVP 和 MVVM 的图示]（http://www.ruanyifeng.com/blog/2015/02/mvcmvp_mvvm.html “MVC，MVP 和 MVVM 的图示”）
