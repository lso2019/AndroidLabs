# **Flutter介绍**
## **一、Flutter是什么**
Flutter 是 Google 用以帮助开发者在 iOS 和 Android 两个平台开发高质量的原生应用的全新移动 UI 框架;  
Flutter 的目标是解决移动开发中的两个重要问题：其一是实现原生应用的性能和与平台的集成，其二是提供一个多平台，可移植的 UI 工具包来支持高效的应用开发。 
## **二、Flutter支持的开发环境**
1. 安装环境:  
支持在Windows、macOS、Linux和Chrome OS
上开发。
2. 编辑器：  
支持在IntelliJ，VS Code或Emacs开发环境。
## **三、Flutter的框架介绍**
Flutter 是一个跨平台（Android 和 iOS）的移动开发框架，使用的是 Dart 语言。和 React Native 不同的是，Flutter 框架并不是一个严格意义上的原生应用开发框架。

Flutter 的目标是用来创建高性能、高稳定性、高帧率、低延迟的 Android 和 iOS 应用。并且开发出来的应用在不同的平台用起来跟原生应用具有一样的体验。不同的平台的原生体验应该得到保留，让该应用看起来同整个系统更加协调。不同平台的滚动操作、字体、图标 等特殊的特性 应该和该平台上的其他应用保持一致，让用户感觉就像操作原生应用一样。比如，返回图标 Android 和 iOS 是不一样的；滚动内容滚动到底的反馈也是不一样的。
## **四、Flutter的优势**
1. 热重载  
Flutter 最受欢迎的功能之一是其快速，保留程序状态的热重载 （hot reload）。 您可以在 Flutter 应用程序运行时对其进行更改，重新加载应用程序的代码，将其从之前的操作位置继续下去。一次热重载通常用不到一秒钟。 如果您的应用遇到错误，您通常可以修复错误，然后继续，就像错误从未发生过。 即使你必须完全重新加载，它也是很快速的。
2. 性能优越  
自带的高性能渲染引擎（Skia）进行自绘，渲染速度和用户体验堪比原生。
3. UI强大,富有表现力  
Flutter内置美丽的Material Design和Cupertino（iOS风格）widget、丰富的motion API、平滑而自然的滑动效果和平台感知，为您的用户带来全新体验。
4. 跨平台
可以同时支持Android和macOS的开发

## **五、Flutter 应用和原生应用的区别**
Flutter 应用运行在一个用 C++ 写的引擎中，Flutter 应用可以看做是一个游戏 App，代码都是在 引擎中运行。
对于 Android 应用来说，Flutter 框架在引擎中实现了一个 继承于 SurfaceView 的 FlutterView 。用户所看到的 UI 都是在这个 SurfaceView 中显示。如果要和原生平台功能交互，则可以在 Activity 中使用 FlutterView，并通过 Flutter 提供的消息 API 和原生平台收发消息。
## **六、Flutter 应用和 React Native 应用的区别**
- 使用的编程语言不同，Flutter 使用的是 谷歌自己新的 Dart 语言，新的语言可以吸收很多其他成功编程语言的特性，更具有表达性，编码效率更高，而 React Native 使用的 JavaScript 语言。
- React Native 是把应用编译为原生控件运行，这样在转换的时候会有性能损耗，并且有些平台特性可能无法做成跨平台使用

