# mprpc
基于muduo网络库和protobuf实现的分布式框架

本项目是一个rpc框架，可以自定义rpc方法上传或调用

项目准备：muduo和pprotobuf安装

muduo安装参考：
https://blog.csdn.net/QIANGWEIYUAN/article/details/89023980

protobug安装参考：
自己在github源代码下载地址：https://github.com/google/protobuf
源码包中的src/README.md，有详细的安装说明，安装过程如下：

      1、解压压缩包：unzip protobuf-master.zip
      
      2、进入解压后的文件夹：cd protobuf-master

      3、安装所需工具：sudo apt-get install autoconf automake libtool curl make g++ unzip

      4、自动生成configure配置文件：./autogen.sh

      5、配置环境：./configure

      6、编译源代码(时间比较长)：make

      7、安装：sudo make install

      8、刷新动态库：sudo ldconfig

项目介绍和使用：待更新

zookeeper的使用参考：https://www.cnblogs.com/xinyonghu/p/11031729.html


整体代码参考来源：腾讯课堂/施磊/mprpc项目
