# Agora iOS Tutorial for Swift - 1to1

*Read this in other languages: [English](README.en.md)*

这个开源示例项目演示了如何生成DynamicKey，实现1对1视频通话。

DynamicKey的生成算法需要去 [https://github.com/AgoraIO/AgoraDynamicKey](https://github.com/AgoraIO/AgoraDynamicKey) 下载导入项目

本开源项目使用 **Swift** 语言。

## 运行示例程序
首先在 [Agora.io 注册](https://dashboard.agora.io/cn/signup/) 注册账号，并创建自己的测试项目，并开通App Certificate，获取到 AppID 和 AppCertificate。将 AppID 填写进 AppID.swift

```
let AppID: String = "Your App ID"
let AppCertificate: String = "Your App Certificate"
```



最后使用 XCode 打开 Agora DynamicKey iOS.xcodeproj，连接 iPhone／iPad 测试设备，设置有效的开发者签名后即可运行。

## 运行环境
* XCode 8.0 +
* 两台 iOS 真机设备
* 不支持模拟器

## 联系我们

- 完整的 API 文档见 [文档中心](https://docs.agora.io/cn/)
- 如果在集成中遇到问题, 你可以到 [开发者社区](https://dev.agora.io/cn/) 提问
- 如果有售前咨询问题, 可以拨打 400 632 6626，或加入官方Q群 12742516 提问
- 如果需要售后技术支持, 你可以在 [Agora Dashboard](https://dashboard.agora.io) 提交工单
- 如果发现了示例代码的bug, 欢迎提交 [issue](https://github.com/AgoraIO/Agora-iOS-Tutorial-Swift-1to1/issues)

## 代码许可

The MIT License (MIT).
