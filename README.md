# react-native-wx-alipay-pay
> react-native版 微信支付，支付宝 插件
> 本插件基于 [xiaozhicheng/react-native-pay](https://github.com/xiaozhicheng/react-native-pay) 做了bug修补

## iOS
### Step1
在工程target的```General``` -> ```Link Frameworks and Libraries``` -> 加入```libsqlite3.tbd, libc++.tbd, libz.tbd```
### Step2
在工程target的```General``` -> ```Link Frameworks and Libraries``` -> 加入```AlipaySDK.framework，CoreMotion.framework```(注意: 加入的AlipaySDK.framework需要是插件支付宝文件里的AlipaySDK.framework)
### Step3
在工程target的```Build Settings```-> ```Frameworks Search Paths``` -> 加入```"$(SRCROOT)/../node_modules/react-native-wx-alipay-pay/ios/PaySdk/支付宝"```

___请勿使用在生产环境上，本仓库处于开发，调试状态___
