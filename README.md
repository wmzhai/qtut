# QT入门介绍

# QT简介

## QT是什么

QT是一个跨平台的C++应用程序开发框架，在Windows平台上比MFC更简单，且很容易可以扩展到其他平台。

QT侧重于GUI程序开发，类似于MFC，不过目前QT能够支持更加广泛的功能：
* 数据库
* 硬件
* XML
* WebKit
* 网络
* 多媒体
* OpenGL

## QT历史

* 1991：Eirik和Nord开始开发支持X11和Windows的QT
* 1994: 二人毕业于挪威理工并创立了TrollTech
* 2005：QT4发布
* 2008：Nokia收购QT
* 2011：Digia收购QT
* 2012:  QT5发布，和QT4不直接兼容
* 2016：QT5.6发布


## QT的目的

* 通过一份代码实现跨平台程序开发，Write once, Compile everywhere
* 在每个平台上具备原生(Native)应用的速度
* 在每个平台上具备原生(Native)应用的外貌
* 尽可能精简统一API设计，更加容易使用，并产生更高的生产效率
* 模块化设计，可以灵活按需配置

### 跨平台程序开发

http://doc.qt.io/qt-5/supported-platforms.html

Write Once, Compile Everywhere

### 原生(Native)应用的速度

* 跨平台开发框架往往在运行速度上会有明显折扣（Adobe Air, H5 App等）
* QT构建在原生的图形引擎之上
* QT应用程序通过编译生成原生程序，速度没有任何折扣

### 原生(Native)应用的外貌

### 精简统一API设计

* QT本身提供跨平台构建工具和IDE工具(QtCreator)
* 在不同平台上提供完全一致的API设计
* 开发人员不需要了解平台底层设计就可以快速入门编写程序
* 在不同操作系统上提供平台独立的封装

### 模块化设计

* QT是模块化构建的，所有的模块都具备类似的设计和API样式，而模块可以灵活组合
* 完整内容可以参考 http://doc.qt.io/qt-5/qtmodules.html


## 谁在用QT

* Google地球
* Adobe Photoshop
* Autodesk Maya
* Robomongo（开源）
* Mathematica
* Opera
* Skype
* VirtualBox
* VLC
* 极品飞车
* WPS Office
* Michelin, Intel, HP, Samsung, Blackberry, ABB, AMD, Epson, HONDA, Cannon,  …



## 为什么用QT

* 跨平台支持：QT支持Windows，Mac，Linux，安卓，iOS，嵌入式系统等
* 学习难度低：QT要比MFC简单很多
* 文档系统全面质量高
* 样例程序丰富可参考
* 开发效率高
* 界面美观：QT支持CSS，可以很方便的写出很炫的界面
* 很容易做国际化
