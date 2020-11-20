# 参考资料

本项目用于记录一些在日常开发、学习过程中收集到的参考资料，包括单不限于博客、开源项目、公众号文章、微博等内容。

## 转载原则

本项目在转载相关内容时，将遵循以下原则：

1. 本项目所收集的全部内容都将**注明作者**。
2. 我将尽量引用**原创内容**，当相关内容没有标注 *“转载”* 或 *“原文地址”* 时，我将认为该内容为原创内容。
3. 为了方便再次查阅，我将按照*个人习惯*在本文件内制作索引，并视情况在链接后增加备注/个人理解/总结。
4. 针对本项目中的所有转载内容，如有侵犯，请提 issues，核实后将会**删除/修改**相关链接并**致歉**。
5. 对于项目内转载的所有内容，本人**不对其正确性、真实性负责**。

## 转载形式

目前本项目将采用 **直接引用链接** 的形式进行转载。

> 虽然这样难免会出现文章链接失效的情况，但是考虑到版权以及引流等问题，本项目将暂时不会直接保存相关文章的内容。

## 目录

> 以下内容的分类、顺序等全部内容均随时可能发生变化。

- 依赖管理工具
  - [Swift Package Manager 使用](#swift-package-manager-使用撬动代码的小秋)
- 开源
  - [同时支持CocoaPods、Carthage、SPM的开源类库](#同时支持cocoapodscarthagespm的开源类库alexiscn)
  - [Namecheap](#namecheap)
- 自动化
  - [如何打造一个让人愉快的框架](#如何打造一个让人愉快的框架王巍-onevcat)
  - [iOS 组件化开发（四）：fastlane实现pod自动化](#ios-组件化开发四fastlane实现pod自动化linxunfeng)
  - [一行命令发布 Pod 框架](#一行命令发布-pod-框架ripperhe)
- UI 效果
  - [全新 iPhone 12 发布，再谈 iPhone 屏幕尺寸](#全新-iphone-12-发布再谈-iphone-屏幕尺寸北极熊不不)
  - [iOS 文本对齐，如何像素般精确还原设计稿](#ios-文本对齐如何像素般精确还原设计稿gao-jiji)
- Swift
  - [Unmanaged](#unmanaged)
- iOS 第三方库
  - [Rxswift教程](#rxswift教程lzc128)
- 代码规范
  - [All Acronyms](#all-acronyms)

## 正文

### 依赖管理工具

#### [Swift Package Manager 使用](https://juejin.cn/post/6871489791213436941#heading-26)：撬动代码的小秋

关于 SwiftPM 的详细使用教程。

### 开源

#### [同时支持CocoaPods、Carthage、SPM的开源类库](https://shuifeng.me/2020/03/02/create-ios-frameworks.html)：alexiscn

文章从创建项目开始，讲述了如何令一个框架同时支持 CocoaPods、Carthage、SPM 三种代码管理工具。

#### [Namecheap](https://www.namecheap.com/logo-maker/app/)

免费的设计生成 logo 的网站。可以为开源库制作 logo （我所有的开源项目的 logo 都是用这个网站制作的。）

### 自动化

#### [如何打造一个让人愉快的框架](https://onevcat.com/2016/01/create-framework)：王巍 (onevcat)

关于如何设计框架。文章中有一个使用 `fastline` 进行发版的脚本很有参考意义。

#### [iOS 组件化开发（四）：fastlane实现pod自动化](https://juejin.cn/post/6844903588020355080)：LinXunFeng

有关如何使用 `fastline` 本身，以及如何使用 `fastline` 进行 pod 发布。

#### [一行命令发布 Pod 框架](https://ripperhe.com/2017/03/30/fastlane-pod/)：ripperhe

如何自动化 pod 发布流程。

### UI 效果

#### [全新 iPhone 12 发布，再谈 iPhone 屏幕尺寸](https://sspai.com/post/63214)：北极熊不不

详细列举了 iPhone 12 系列的屏幕变化，同时还包括了一些细节、以及适配相关的内容。例如该篇文章中还谈到了状态栏高度的改变。

#### [iOS 文本对齐，如何像素般精确还原设计稿](https://zhuanlan.zhihu.com/p/27572662)：Gao JiJi

该文章又名 “如何和 UI 对抗”、“精致的开发者如何做出完美的 App”。文章研究了在 iOS 上如何设置字体，其效果才能与 Sketch 上的效果保持一致。

### Swift

#### [Unmanaged](https://nshipster.cn/unmanaged/)：Nate Cook

主要讲解 Swift 中，内存管理相关的内容，以及 `Unmanaged` 的使用。

### iOS 第三方库

#### [Rxswift教程](https://www.bilibili.com/video/BV1Hb411b7LD)：lzc128

RxSwift 的**视频**教程，发布在 B站。

### 代码规范

#### [All Acronyms](https://www.allacronyms.com)

输入一个单词，可以查找该单词的缩写。用来查变量名的时候可以使用。例如说输入 `Implement`，将返回 `impl`。
