# Agora Online Chorus

*Read this in other languages: [English](README.en.md)*

这个开源示例项目演示了 Agora 合唱功能。

在这个示例项目中包含了以下功能：

- 加入通话和离开通话；

- 扮演播放着角色，播放伴奏；

- 扮演歌手角色，唱歌；

## 获取SDK
联系声网商务下载 Android 平台合唱 SDK。详情请洽 sales@agora.io ，电话 4006326626。

## API 调用顺序

![chorus.png](chorus.png)

## 运行示例程序
首先在 [Agora.io 注册](https://dashboard.agora.io/cn/signup/) 注册账号，并创建自己的测试项目，获取到 AppID。将 AppID 填写进 "app/src/main/res/values/strings.xml"

```
<string name="agora_app_id"><#YOUR APP ID#></string>
```


最后用 Android Studio 打开该项目，连上设备，编译并运行。

也可以使用 `Gradle` 直接编译运行。

## 运行环境
- Android Studio 3.1 +
- 真实 Android 设备 (Nexus 5X 或者其它设备)
- 部分模拟器会存在功能缺失或者性能问题，所以推荐使用真机

## 联系我们
- 完整的 API 文档见 [文档中心](https://docs.agora.io/cn/)
- 如果在集成中遇到问题, 你可以到 [开发者社区](https://dev.agora.io/cn/) 提问
- 如果有售前咨询问题, 可以拨打 400 632 6626，或加入官方Q群 12742516 提问
- 如果需要售后技术支持, 你可以在 [Agora Dashboard](https://dashboard.agora.io) 提交工单
- 如果发现了示例代码的 bug, 欢迎提交 [issue](https://github.com/AgoraIO-Community/Agora-Online-Chorus/issues)

## 代码许可
The MIT License (MIT).
