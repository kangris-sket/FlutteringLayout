# FlutteringLayout
[![Download](https://img.shields.io/badge/download-App-blue.svg)](https://raw.githubusercontent.com/jenly1314/FlutteringLayout/master/app/app-release.apk)
[![Jitpack](https://jitpack.io/v/jenly1314/FlutteringLayout.svg)](https://jitpack.io/#jenly1314/FlutteringLayout)
[![API](https://img.shields.io/badge/API-15%2B-blue.svg?style=flat)](https://android-arsenal.com/api?level=15)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/mit-license.php)
[![Blog](https://img.shields.io/badge/blog-Jenly-9933CC.svg)](http://blog.csdn.net/jenly121)
[![QQGroup](https://img.shields.io/badge/QQGroup-20867961-blue.svg)](http://shang.qq.com/wpa/qunwpa?idkey=8fcc6a2f88552ea44b1411582c94fd124f7bb3ec227e2a400dbbfaad3dc2f5ad)

FlutteringLayout for Android 一个直播间点赞桃心飘动效果的控件。

## Gif 展示
![Image](GIF.gif)

## 引入

### Maven：
```maven
<dependency>
  <groupId>com.king.view</groupId>
  <artifactId>flutteringlayout</artifactId>
  <version>1.1.0</version>
  <type>pom</type>
</dependency>
```
### Gradle:
```gradle
compile 'com.king.view:flutteringlayout:1.1.0'
```
### Lvy:
```lvy
<dependency org='com.king.view' name='flutteringlayout' rev='1.1.0'>
  <artifact name='$AID' ext='pom'></artifact>
</dependency>
```
###### 如果Gradle出现compile失败的情况，可以在Project的build.gradle里面添加如下：（也可以使用上面的GitPack来complie）
```gradle
allprojects {
    repositories {
        maven { url 'https://dl.bintray.com/jenly/maven' }
    }
}
```

## 示例

布局
```Xml
    <com.king.view.flutteringlayout.FlutteringLayout
        android:id="@+id/flutteringLayout"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_marginBottom="10dp"
        app:duration="3000"
        app:enter_duration="300"
        app:scale="1.0"/>
```

添加桃心代码
```Java
flutteringlayout.addHeart();
```

## 赞赏
如果您喜欢FlutteringLayout，或感觉FlutteringLayout帮助到了您，可以点右上角“Star”支持一下，您的支持就是我的动力，谢谢 :smiley:<p>
也可以扫描下面的二维码，请作者喝杯咖啡 :coffee:
    <div>
        <img src="https://image-1252383324.cos.ap-guangzhou.myqcloud.com/pay/wxpay.png" width="280" heght="350">
        <img src="https://image-1252383324.cos.ap-guangzhou.myqcloud.com/pay/alipay.png" width="280" heght="350">
        <img src="https://image-1252383324.cos.ap-guangzhou.myqcloud.com/pay/qqpay.png" width="280" heght="350">
    </div>

## 关于我
   Name: <a title="关于作者" href="https://about.me/jenly1314" target="_blank">Jenly</a>

   Email: <a title="欢迎邮件与我交流" href="mailto:jenly1314@gmail.com" target="_blank">jenly1314#gmail.com</a> / <a title="给我发邮件" href="mailto:jenly1314@vip.qq.com" target="_blank">jenly1314#vip.qq.com</a>

   CSDN: <a title="CSDN博客" href="http://blog.csdn.net/jenly121" target="_blank">jenly121</a>

   Github: <a title="Github开源项目" href="https://github.com/jenly1314" target="_blank">jenly1314</a>

   加入QQ群: <a title="点击加入QQ群" href="http://shang.qq.com/wpa/qunwpa?idkey=8fcc6a2f88552ea44b1411582c94fd124f7bb3ec227e2a400dbbfaad3dc2f5ad" target="_blank">20867961</a>
   <div>
       <img src="https://image-1252383324.cos.ap-guangzhou.myqcloud.com/jenly666.png">
       <img src="https://image-1252383324.cos.ap-guangzhou.myqcloud.com/qqgourp.png">
   </div>

   
   
   
