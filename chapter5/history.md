
# 计算机历史

## 机械计算机


### 冯 诺依曼结构和电子计算机


### UNIX家族历史


事实上，UNIX从诞生开始的那一天就一直在背后影响着整个世界

起源于贝尔实验室


#### POSIX标准

#### BSD 家族


实际上，苹果公司的一系列产品，都是由修改过的开放源代码的freeBSD内核开发的，苹果将这个修改版本的内核称之为Darwin,并在Darwin内核的基础上创建如Mac OSX, iOS这一系列用户友好的操作系统，使得很多对计算机知识不多的非专业用户也能较好的使用UNIX操作系统。

同时，经过一些越狱的用户的研究，Sony的PlayStation设备其实也使用了一个修改版本的freeBSD内核。

#### Linux 家族
Linux是一个开源的POSIX兼容的操作系统内核，他由芬兰的大学生Tovarls Linus开发，并以企鹅为吉祥物。基于这个内核产生了很多的操作系统，比如当今的Android操作系统,Kindle阅读设备使用的操作系统，以及服务器上使用较多的Redhat Linux Enterprise, CentOS, Ubuntu Server, 桌面用户较多的Fedora, Ubuntu以及国内的Deepin等等，同时世界上排名靠前的超级计算机也绝大多数都在使用Linux。但是Linux的使用需要用户有一定的专业知识，存在较高的用户门槛，对普通用户并不友好。从事科研行业的人也利用Linux强大的处理能力来进行科研活动。

> 想感受到Andorid是一个Linux内核的操作系统? 你可以尝试在Android手机上下载一个名为'Terminl Emulator'的应用，通过他你可以和手机内部的shell通信，可以试着学习如ls,ps,ping等这些简单的Linux操作系统指令，你可能会体验到终端(Terminal)酷酷的感觉


#### 越狱和Root
越狱和Root实际上都是利用类UNIX系统内核或具有较高权限程序的一些漏洞，从而获取系统的最高管理权限，即Root用户的权限。在类UNIX系统中，Root用户几乎拥有对所有资源的控制权。

iOS和PlayStation以及Kindle设备在越狱后可以安装非官方的产品，而Android手机在Root之可以对系统进行更多的控制和改动。


### Windows系统
目前Windows系列的操作系统占据了绝大多数的桌面市场,特点是操作简单，用户友好，软件支持较多等特点。

在Windows XP之前，Microsoft公司采用了以MS-DOS为基础的方式开发图形环境，在XP及之后的操作系统中，均使用了新的Windows NT(New Technology)内核。令人意外的是，虽然Windows和其他UNIX操作系统的模式存在很大差别，Windows NT内核也是POSIX兼容的操作系统。




###  不同操作系统有什么区别

- 可执行程序的格式不同，如Windows下下载的可执行程序的格式是exe，Android下的可执行程序格式是apk, Mac OSX的是app, iOS的是ipa,　他们之间的可执行程序的格式存在比较大差距，不能通用。

-  支持的处理器架构不同，如Mac OSX支持PowerPC和x86架构，Android和iOS一般为Arm架构，Windows多为支持x86,x64架构的处理器，不同架构的处理器架构存在很大差异，这也是影响软件移植性的主要原因。如Android的x86架构CPU就会存在很多应用不能安装的情况。

- 软件，界面和操作模式不同。
