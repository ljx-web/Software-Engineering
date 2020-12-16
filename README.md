# Software-Engineering

出于简单起见，该文件系统是基于内存的，以下是各个文件:

 ![img](F:\Typora\typora-pic\20180820120042793)
1、内存资源管理（Disk.h, Disk.cpp）
2、文件读写接口（File.h, File.cpp）
3、主程序（main.cpp, my_shell.cpp）

目录项数据结构：
 ![img](F:\Typora\typora-pic\20180820120219859)
一个目录项包含了文件名和文件类型，当文件为目录时，起始盘块指示了目录表所在的盘块号，当文件为文件时，起始盘块指示了FCB所在的盘块号。

目录表数据结构：
 ![img](F:\Typora\typora-pic\20180820120238442)
文件控制块数据结构：
 ![img](F:\Typora\typora-pic\20180820120248796)