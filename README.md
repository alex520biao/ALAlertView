# ALAlertView

## 功能简介

简明扼要的描述功能

## 使用方法&Demo
### demo code
`通过demo code 展示此pod的主要功能，使用者阅读了demo code应该可以了解pod的大部分功能，API设计应尽量简洁易懂`

``` objective-c
//demo code here
```
### 公开类

介绍主要类的功能职责，例如：

	AFNetworkReachabilityManager：监听网络状态变化
	[[AFNetworkReachabilityManager sharedManager] setReachabilityStatusChangeBlock:^(AFNetworkReachabilityStatus status) {
	
		NSLog(@"Reachability: %@", AFStringFromNetworkReachabilityStatus(status));
	
	}];
	[[AFNetworkReachabilityManager sharedManager] startMonitoring];

### 注意事项(可选)



## 内部实现原理（可选）



## 安装

目前都使用cocoapods安装，在Podfile中加入

``` ruby 
	pod "ALAlertView" 
```

## 维护者

alex520biao <alex520biao@163.com>

## 版权声明

ALAlertView 是xxxx内部项目，默认不对外开源。
