# **Flutter简介**

Flutter是Google在2015年推出的移动UI框架，可快速在iOS和Android上构建高质量的原生用户界面

## **Flutter的优势**
### 1.*快速开发*
Flutter的热重载可帮助您快速地进行测试、构建UI、添加功能并更快地修复错误。在iOS和Android模拟器或真机上可以在亚秒内重载，并且不会丢失状态 
### 2.*富有表现力和灵活的UI8
快速发布聚焦于原生体验的功能，分层的架构允许您完全自定义，从而实现难以置信的快速渲染和富有表现力、灵活的设计。
### 3.*原生性能*
Flutter包含了许多核心的widget，如滚动、导航、图标和字体等，这些都可以在iOS和Android上达到原生应用一样的性能。
## **Flutter适用人群**
Flutter适用于希望以更快的方式构建漂亮的移动应用程序的开发人员，或者通过单一研发投入得更多用户的方式(同一份代码支持IOS和Android)。

  Flutter也适用于需要领导移动开发团队的工程经理。 Flutter允许经理创建一个移动应用开发团队(而不是IOS和Android两个团队)，统一大家的开发方式以更快地向向iOS和Android发布相同的功能，同时，并降低维护成本。
 
## **Flutter可以构建什么类型的应用程序**
Flutter针对想要在Android和iOS上运行的2D移动应用进行了优化。您可以使用Flutter构建全功能应用程序，包括相机、地理位置、网络、存储、第三方SDK等。

## **Flutter的优缺点**
### ***优点***
1.支持AOT的Dart语言，AOT方式编译成机器码（ARM），执行效率也比JavaScript高。

2.一套代码运行在多个平台，做到真正的跨平台。

3.JIT & AOT运行模式，支持开发时的快速迭代和正式发布后最大程度发挥硬件性能。Flutter所使用的Dart语言同时支持AOT和JIT运行方式，JIT模式下还有一个备受欢迎的开发利器“热刷新”（Hot Reload），即在Android Studio中编辑Dart代码后，只需要点击保存或者“Hot Reload”按钮，就可以立即更新到正在运行的设备上，不需要重新编译App，甚至不需要重启App，立即就可以看到更新后的样式。

4.Flutter本身支持Android和iOS两个平台，提供了两套设计语言的控件实现Material & Cupertino，可以帮助App更好地在不同平台上提供原生的用户体验，还包含了许多核心的widget，如滚动、导航、图标和字体等，这些都可以在iOS和Android上达到原生应用一样的性能

5.兼容性上，Flutter 提供的 widget 都是基于 skia来实现和精心定制的，与具体平台没关，所以能保持很高的跨 os 跨 os version 的兼容性。

6. Flutter可以复用现有的Java、Swift或ObjC代码，访问iOS和Android上的原生系统功能和系统SDK

7. 通过使用Isolates,可以充分利用多核性能。

8.相较于其他跨平台应用，art语言原生的支持面向对象，函数式编程，响应式编程，泛型，并发。
### ***缺点***
1.第三方库较少，许多常用的复杂控件还需要自己实现。

2.调用系统的service仍然需要封装接口，仍然还是需要懂得native开发，简单点说就是需要调用android，IOS的服务，需要写两套android，Ios的代码，然后利用dart调用。

3.Dart 语言很不友好，括号较多，各种嵌套，可读性较差。

4.Flutter官方没有对平板下的运行情况进行测试，有可能一些组件存在issue，目前所有widget都没有对平板进行特殊适配。

5.不支持3d

6.版本不成熟，beat版本还有许多bug，需要到release才能真正用于商业开发。

7.官方提供的组件大部分都以 Material Design 为主，iOS风格的组件比较少，对于需要用到 iOS 风格组件的情况，都需要自己手动绘制组件。

8.社区尚不成熟，开发中遇到问题，不太容易快速找到解决方案，需要踩比较多的坑。

9.Flutter的在调试模式和Release模式下性能差别很大。如果你调试时发现性能差，就最好试试release模式。

