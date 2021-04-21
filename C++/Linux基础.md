# Linux基础

**查看进程指令**

ps命令

-a，查看所有

-u，以用户（user）的格式显示

-x, 显示后台进程运行参数

-ef，以全格式显示进程所有信息，包括父进程Pid，创建人，创建时间，进程号。等等

一般项目中，我们首先要查询一个进程，并对其进行删除会用一下命令

ps -a | grep helloworld 或

ps -ef |grep helloworld 或者其他

![image-20210409211554787](C:\Users\YJDELL\AppData\Roaming\Typora\typora-user-images\image-20210409211554787.png)

