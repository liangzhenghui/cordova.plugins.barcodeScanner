欢迎加入Cordova/phonegap 231809968 交流群
原地址在此https://github.com/phonegap/phonegap-plugin-barcodescanner
本插件只是对其进行部分修改。
# cordova.plugins.barcodeScanner
对cordova.plugins.barcodeScanner插件进行了界面美化以及竖屏显示
![image](https://github.com/liangzhenghui/cordova.plugins.barcodeScanner/blob/master/screenshots/demo.jpg)

引入方式：
当安装完插件之后，找到插件安装到项目的路径，比如我这里是
D:\cordovademo\test\plugins\com.phonegap.plugins.barcodescanner\src\android\LibraryProject
将该依赖包引进来。
比如我用的是android studio
步骤如下:
File->new->import Module 选择 D:\cordovademo\test\plugins\com.phonegap.plugins.barcodescanner\src\android\LibraryProject 导入。
导入成功之后。右键项目名->Open Modules Settings ->Dependencies->点击加号选择Module dependency 选择CaptureActivity
大功告成。
