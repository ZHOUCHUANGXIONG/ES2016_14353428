#### DOL框架描述
DOL是一个软件开发框架编程并行应用程序。DOL允许指定基于计算Kahn进程网络模型的应用范围和特点，基于SystemC仿真引擎。此外，劳工部提供了基于XML规范的格式来描述一个多处理器系统上的并行应用程序的实现，包括结合和映射。

#### 开发环境配置
* 1 安装一些必要的环境：$ sudo apt-get update，$ sudo apt-get install ant，$ sudo apt-get install openjdk-7-jdk，$ sudo apt-get install unzip
* 2 下载dolethz.zip和systemc文件
* 3 解压文件：将dolethz.zip解压到新建的 dol文件夹中$ unzip dol_ethz.zip -d dol，解压systemc
* 4 编译systemc：$ cd ../dol进入dol文件夹，pwd,表明当前的工作路径,修改build_zip.xml文件.
* 5 编译dol：$ ant -f build_zip.xml all，运行第一个例子。
    运行成功结果如图：
![aadqd](https://cloud.githubusercontent.com/assets/22741656/20216698/02676a1c-a857-11e6-93db-6165acc1863f.png)

#### 实验感想
安装过程按部就班，要学会阅读编译代码，找到关键的语句可以自行排查错误，而不用去询问其他同学。

    
