
本实验将实现如下功能：本实验采用LWIP的RAW编程方法实现TCP Client功能，默认开启DHCP自动获取IP地址。电脑端打开网络调试助手，网络调试助手做服务器，所以选择TCP Server协议。开发板做TCP客户端，在开发板上设置好服务器的IP地址，也就是电脑的IP地址，然后按下KEYUP键连接。最后就可以通过网络调试助手向开发板发送数据，按下开发板的KEY0键也可以向网络调试助手发送数据。

注意：本例程未使用了UCOS操作系统，默认开启DHCP,本例程为MiniSTM32开发板ENC28J60网络实验例程。

            	广州市星翼电子科技有限公司
                电话：020-38271790
                传真：020-36773971
	       	购买：http://shop62103354.taobao.com
                      http://shop62057469.taobao.com
                公司网站：www.alientek.com
         	技术论坛：www.openedv.com
