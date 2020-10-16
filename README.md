# java-
Java课程实验作业项目仓库
# 阅读程序

一、实验目的
1.Java应用程序有四个类，分别为PC,CPU,HardDisk类和主类Test。
2.学习并使用类并构造对象
3.学习并使用构造方法，在类中构建对象。
4.学习并使用this关键字。
5.学习并使用访问权限

二、实验过程
本次实验设计CPU速度和硬盘容量的过程除了主类Test外还需要列举三个子类，名字分别为PC、CPU、HardDisk和Test.CPU、HarkDisk两个用于设置参数，另一个PC用于确定输入格式和调用实参，本次用的是show()方法，
最后主类设定数值，创建PC，从而将结果输出。


三、核心方法
CPU类要求getSpeed()返回speed的值，要求setSpeed(int m)方法将参数m的值赋值给speed,HardDisk类要求getAmount()返回amount的值，要求setmount(int m)方法将参数m的值赋值给amount,PC类要求
setCPU(CPU C)J将参数c的值赋值给cpu,要求setHardDisk(HardDisk h)方法将参数h的值赋值给HD，要求show()方法能显示cpu的·速度和硬盘的容量。
主类Test的要求(1)main方法中建立一个cpu,cpu将本身的speed设置为2200；（2)main方法中建立一个HardDisk对象disk,disk将本身的amout设置为200；（3）main方法中建立一个PC对象pc
(4)pc调用setCPU(CPU c)方法，调用时实参是cpu
（5）pc调用setHardDisk(HardDisk h)方法，调用时实参是disk
(6)pc调用shoe()方法


四、实验结果
CPU速度2200
CPU型号i7-9750H
硬盘容量200
硬盘速度500

五、实验感想
在实验过程中，了解了类与对象的使用， 感受到了学习Java的快乐。使用this关键字来区分当前对象，对象的创建时通过构造方法来完成的 其功能是完成对象的初始化 ，访问权限是每一个面向对象语言都会有的一个特色
他是通过某一些固定的关键字能够给类中的成员指定外部人员的访问权限。通常较多的是public,private,protected.
