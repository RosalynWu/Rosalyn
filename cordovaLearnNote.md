# 如何搭建cordova环境（安卓）
## 工具安装：
#### 1、Webstorm/Idea
#### 2、vistul studio（最好13以上）
## 库安装（所有库都需要配置系统变量）：
#### 1、java jdk
#### 2、android sdk
#### 3、python必须是2.X版本
#### 4、nodejs
## cordova安装
#### 第一步：（全局）安装cordova
> npm install (-g) cordova
#### 第二步：创建一个app
> cordova create hello com.example.hello HelloWorld
#### 第三步：添加平台
> cordova platform add android --save
#### 第四步：运行app
> cordova build android
> 注意：在运行app之前如果在线下载gradle.zip时间过长可手动进行设置，具体可参照如下：
```javascript
document.getElementById('file')
```
#### 当执行命令 "cordova build android"时，会提示说"could not find gradle wrapper within android sdk,might need to update your android sdk"的解决办法：
##### Try to copy the templates directory of Android Studio: "C:\Program Files\Android\Android Studio\plugins\android\lib\templates" to your android sdk tools directory: "C:\Android\sdk\tools" This did the trick for me :)



