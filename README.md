## EasyRTMP ##

### **EasyRTMP**是什么？ ###

EasyRTMP是EasyDarwin团队开发的一套RTMP直播推送功能组件，内部集成了包括：基本RTMP协议、断线重连、异步推送、环形缓冲区、推送网络拥塞自动丢帧、缓冲区关键帧检索、事件回调(断线、音视频数据回调)，通过EasyRTMP我们就可以避免接触到稍显复杂的RTMP推送或者客户端流程，只需要调用EasyRTMP的几个API接口，就能轻松、稳定地进行流媒体音视频数据的推送，支持市面上绝大部分的RTMP流媒体服务器，包括Red5、Ngnix_rtmp、crtmpserver等主流RTMP服务器，全平台支持：Windows、Linux、ARM(各种交叉编译工具链)、Android、iOS;

- **我们同时提供Windows、Linux、ARM、Android、IOS版本的EasyRTMP SDK**：EasyRTMP SDK商业使用需要经过授权才能永久使用，商业授权方案可以邮件发送至[support@easydarwin.org](mailto:support@easydarwin.org "EasyDarwin support mail")或者通过电话Tel：**13718530929** 进行更深入的技术与合作咨询；

### 调用方法 ###

- **EasyRTMP_File**：EasyRTMP做为RTMP推送端，将本地文件推送到RTMP流媒体服务器；
- **EasyRTMP_RTSP**：将RTSP/RTP数据获取到本地，再通过EasyRTMP推送到RTMP服务器；
- **Android**：Android安卓RTMP直播推流，采集安卓手机前/后摄像头、麦克风音视频推送直播；
- **iOS**：iOS苹果RTMP直播推流，采集苹果手机前/后摄像头、麦克风音视频推送直播；

> 我们在公网部署了一台演示的RTMP服务器系统：http://www.easydss.com:10088/live.html ，支持RTMP直播、服务端录像、检索、回放等功能；

### 编译方法 ###

	Windows平台采用Visual Studio 2010编译

	Linux下执行Builtit文件编译,具体如下：
		chmod a+x Builtit
		
		"**************build stream from EasyRTMP_RTSP demo******************"
		"1. build 32bit program ./Buildit rtsp i386 [target in i386]"	
		"2. build 64bit program ./Buildit rtsp x64 [target in x64]"	
		"3. clean up ./Buildit rtsp clean"
		"-----------------------------------------------------------"
		"**************build stream from EasyRTMP_FILE demo******************"
		"4. build 32bit program ./Buildit file i386 [target in i386]"	
		"5. build 64bit program ./Buildit file x64 [target in x64]"	
		"6. clean up ./Buildit file clean"
		"-----------------------------------------------------------"
		"**************build stream from EasyRTMP_SDK demo*******************"
		"7. build 32bit program ./Buildit sdk i386 [target in i386]"	
		"8. clean up ./Buildit sdk clean"
		"-----------------------------------------------------------"
	

### 调用示例 ###

- EasyRTMP Android：支持前/后摄像头直播、安卓屏幕直播

[https://fir.im/easyrtmp](https://fir.im/easyrtmp "https://fir.im/easyrtmp")

![EasyRTMP Android](http://www.easydarwin.org/github/images/easyrtmpfirim20170409.png)

- EasyRTMP iOS：支持前/后摄像头直播

[https://itunes.apple.com/us/app/easyrtmp/id1222410811?mt=8](https://itunes.apple.com/us/app/easyrtmp/id1222410811?mt=8 "EasyRTMP_iOS")

![](http://www.easydarwin.org/github/images/easyrtmpios20170409.png)

### 调用过程 ###
![EasyRTMP](http://www.easydarwin.org/skin/easydarwin/images/easyrtmp20161101.png)


### 获取更多信息 ###

邮件：[support@easydarwin.org](mailto:support@easydarwin.org) 

WEB：[www.EasyDarwin.org](http://www.easydarwin.org)

Copyright &copy; EasyDarwin.org 2012-2017

![EasyDarwin](http://www.easydarwin.org/skin/easydarwin/images/wx_qrcode.jpg)
