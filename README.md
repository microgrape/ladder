# 为路由器安装梅林固件及ss/ssr客户端，实现全家自动科学上网/翻墙/梯子

在这里介绍一种科学上网方法：仅需要在路由器上配置一次，其他电子设备（包括手机、平板pad、PC、笔记本）无需配置的方法。  
  
**1、一个支持ss/ssr访问的服务器。**  
可以是付费的，也可以是自己买VPS服务器搭建的ss server。笔者使用的付费服务（https://github.com/baacloud/url）  
注：ss=shadowsocks;ssr=shadowsocks-R  

**2、硬件：  一台支持梅林固件的无线路由器。**
那么哪些无线路由器可以刷梅林固件呢？最全的地方应该数koolshare了。  
具体见：https://firmware.koolshare.cn/  

笔者使用的是一台网件Netgear R8500路由器，那么固件可以在这里找到：https://firmware.koolshare.cn/Koolshare_Merlin_Legacy_380/Netgear/R8500/  
最新的固件是X7.9版本。  

2.1 那么R8500具体如何刷梅林固件呢？  
——从原厂固件的控制台，可以直接升级到以chk结尾的X7.4版本的梅林固件：https://firmware.koolshare.cn/Koolshare_Merlin_Legacy_380/Netgear/R8500/X7.4/R8500_380.65_X7.4_happymayday.trx  
——然后在此梅林固件的后台，再更新到X7.9版本的固件即可：https://firmware.koolshare.cn/Koolshare_Merlin_Legacy_380/Netgear/R8500/X7.9/  


**3、软件：**  

3.1 配置梅林固件的软件中心  
![image](https://github.com/microgrape/ladder/blob/main/%E8%BD%AF%E4%BB%B6%E4%B8%AD%E5%BF%83.png)
如上图所示，如果红框里的软件中心版本不是最新的，需要先进行一下更新。  

3.2 离线安装ss/ssr客户端软件  
具体用什么软件呢？非常推荐fancyss（https://github.com/hq450/fancyss）。  
大多数路由器都可以找到自己的对应版本的fancyss。  

安装好了之后，就可以如上面的图中，看到一个红灿灿的“科学上网”。

3.3 科学上网配置  
![image](https://github.com/microgrape/ladder/blob/main/%E7%A7%91%E5%AD%A6%E4%B8%8A%E7%BD%91%E9%85%8D%E7%BD%AE.png)
其实这个环节是最简单的了，只需要把第1节中准备好的支持ss/ssr访问的服务器填入即可。上面就是我配置好的图了。  
保存&应用，然后就可以一直科学上网了。
