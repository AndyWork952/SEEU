# see_u

WKU_Spring_2020_CPS4951

## Windows install
### Get the Flutter SDK
   1.Download the following installation bundle to get the latest stable release of the Flutter SDK:
   https://storage.googleapis.com/flutter_infra/releases/stable/windows/flutter_windows_v1.12.13+hotfix.9-stable.zip
   
   2.Extract the zip file and place the contained flutter in the desired installation location for the Flutter SDK (for example, C:\src\flutter;<b> do not install Flutter in a directory like C:\Program Files\ that requires elevated privileges</b>).
   
### Update your path
1. 此电脑>属性>高级系统设置>环境变量>Administrator Uesr Variables> append the full path to flutter\bin
2. 新建-变量名：PUB_HOSTED_URL，变量值：https://pub.flutter-io.cn
3. 新建-变量名：FLUTTER_STORAGE_BASE_URL，变量值：https://storage.flutter-io.cn

### Run flutter doctor
C:\src\flutter>flutter doctor

<b>根据缺失的提示，下载相应的软件</b>

[-] Android toolchain - develop for Android devices
    • Android SDK at D:\Android\sdk
    ✗ Android SDK is missing command line tools; download from https://goo.gl/XxQghQ
    • Try re-installing or updating your Android SDK,
      visit https://flutter.dev/setup/#android-setup for detailed instructions.
### After the above steps please follow the rules from 
https://flutter.dev/docs/get-started/install/windows#get-the-flutter-sdk

## Mac OS install
https://www.bilibili.com/video/BV11J411n7Zv?p=24 
9分18秒开始

https://flutter.dev/docs/get-started/install/macos
