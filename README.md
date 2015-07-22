JPush-SDK-iOS
=============

这是一个 [极光推送](https://www.jpush.cn/common/products) iOS 版本 SDK 的一个非官方镜像。 

官方开发指南在这里：[http://docs.jpush.io/client/ios_sdk/](http://docs.jpush.io/client/ios_sdk/).

极光推送，使得开发者可以即时地向其应用程序的用户推送通知或者消息，与用户保持互动，从而有效地提高留存率，提升用户体验。平台提供整合了Android推送、iOS推送的统一推送服务。

### 使用 CocoaPods 安装
[CocoaPods](http://cocoapods.org) 是开发 OS X 和 iOS 应用程序的一个第三方库的依赖管理工具。

推荐这样配置 Podfile:

```ruby
# The front repo is prior if conflicted
# CocoaPods private repo
source 'https://github.com/jcccn/PodSpecs.git'
# CocoaPods master repo
source 'https://github.com/CocoaPods/Specs.git'

platform :ios,'7.0'

# ignore all warnings from all pods
inhibit_all_warnings!

pod 'JPush'

```

也可以这样配置Podfile:

```ruby
# CocoaPods master repo
source 'https://github.com/CocoaPods/Specs.git'

platform :ios,'7.0'

# ignore all warnings from all pods
inhibit_all_warnings!

pod 'JPush', :git => 'https://github.com/jcccn/JPush-SDK-iOS.git'

```

### 产品特点
##### <img src="https://www.jpush.cn/res/v3/images/common/v4/product-push-feature-multi.png"> 多种推送方式
- 通知：推送文本内容直接展示在用户的通知栏中。
- 自定义消息：推送自定义的消息内容透传给应用处理。
- 富媒体：推送预先编辑好的图文并茂的HTML页面内容。
	
##### <img src="https://www.jpush.cn/res/v3/images/common/v4/product-push-feature-target.png"> 灵活的推送目标
- 广播推送：向所有的注册用户发送一条广播消息。
- 标签推送：根据属性对用户设置标签分组，向群组用户发送。
- 别名推送：客户端绑定用户别名，向具体的单个用户推送。

##### <img src="https://www.jpush.cn/res/v3/images/common/v4/product-push-feature-user.png"> 用户分群
- 根据 JPush 提供的多条件组合进行用户群组划分，实时筛选实时推送。

##### <img src="https://www.jpush.cn/res/v3/images/common/v4/product-push-feature-history.png"> 推送历史
- 无论是通过Web发送的还是通过API发送的都可以在推送历史记录中查询。

##### <img src="https://www.jpush.cn/res/v3/images/common/v4/product-push-feature-done.png">简单易集成
- 网站后台：通过 JPush 网站后台完成推送以及查看历史、报表，无需技术要求。
- 发送与查询API：开放推送和结果查询的 RESTful API 供开发商可以灵活对接。
- 客户端SDK：简单集成Android， iOS SDK。

##### <img src="https://www.jpush.cn/res/v3/images/common/v4/product-push-feature-stat.png"> 统计与报表
- “推送报表”与“用户统计报表”呈现推送的效果和应用发展趋势。