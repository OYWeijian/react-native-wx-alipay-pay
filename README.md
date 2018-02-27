# react-native-wx-alipay-pay
> react-native版 微信支付，支付宝 插件
> 本插件基于 [xiaozhicheng/react-native-pay](https://github.com/xiaozhicheng/react-native-pay) 做了bug修补

## iOS
### Step1
在工程target的```General``` -> ```Link Frameworks and Libraries``` -> 加入```libsqlite3.tbd, libc++.tbd, libz.tbd```
### Step2
在工程target的```General``` -> ```Link Frameworks and Libraries``` -> 删除```libReactNativePay.a```

___请勿使用在生产环境上，本仓库处于开发，调试状态___
