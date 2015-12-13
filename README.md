# 凉夜APP-Android

##### 提示:因服务器资源限制,已去除服务器URL部分内容[以及对分享功能进行了调整(需自行填入APPID)],非常抱歉!

### 该应用共有三个大模块：<br />
	1. 看看（文字内容，采集自网络）:
		详细：自有国外服务器，提供数据支撑，文字内容同样基于该服务器提供（对于访问速度是最大的性能瓶颈，希望后期有能力可以改善）。当前更新频率为3天更新一次。在Android客户端提供了缓存及下拉刷新操作。在分享方面，目前集成了微信、易信、QQ这几个分享。
	
	2. 有图（图片，每天定时更新）:
		详细：图片源自某门户每天更新的图片，后台服务器每天零时左右定时进行更新。客户端对于服务器端有相应延迟（避免提前请求导致的加载错误）。该项同样提供文字方式的分享（在分享方式上有差别），并提供保存本地及即时设置桌面功能。
	
	3. 关于（关于APP、设置等操作）:
		详细：可在客户端开启[每天自动设置桌面功能(使用两个Service相互监听,保障可正确更新,若开启,该功能会延迟更新.)]、提交反馈、关于等。

###详细资料：<br />
    * 开发工具：Idea 14 .
    * 最小支持Android版本：Android 4.0.3,Android 4.0.4(API LEVEL 15).
    * 编译SDK版本：23.
    * 后台服务器：Centos 6.5
    * 后台服务器编程语言：Python 3.4
    * 是否开源：是.
    * DAO操作：ORMLite

###客户端整体技术：<br />
	* 首页：RadioGroup+Fragment
	* 三大模块：
		1. 看看：ListView
		2. 有图：ViewPager
		3. 关于：ListView+ViewPager+DrawerLayout
	* 共有模块：
		1. 工具栏：自定义ActionBar.
		2. 底部弹出栏：自定义PopupWindow.
		3. 网络工具：使用了Volley,自定义网络工具类.
	
### 如何开始:<br />
	[releaseAPK文件夹内有已经打包好的APK文件,因很多原因本APP未在任何APP市场上架!]先部署源码到IDEA或者Android Studio,然后搜索所有TODO标记,依据标记提示进行相应配置.

### 更新日志:
    1. 2015.12.13 第一次上传.

### 有问题联系:<br />
	博客:http://www.07q.net
	邮箱:pruidong#gmail.com
   
