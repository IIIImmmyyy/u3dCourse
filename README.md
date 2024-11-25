# Android U3D手游安全中级篇

## （上次课程更新时间 2024/11/25）

## 1. 前言
> Android逆向的知识体系复杂多样，技术更新速度更是惊人。但市面上的教程大多还停留在<font color ="#ff0000">**Unity Dll，
> Java内购破解等旧时代产物的知识点，甚至示例的游戏都无法找到。**</font>对让渴望进阶的你找不到方向。现在，一切都将改变。

## 2. 突破现状：与时俱进，引领潮流
> <font color ="#ff0000">**2024**</font>年即将来临，是时候让你的技能也走在<font color ="#ff0000">**时代的前沿**</font>。本课程从U3D引擎的Il2Cpp切入，深度解析Dll与Il2Cpp的关联，教你如何进行Il2Cpp的高级应用，且实战均为<font color ="#ff0000">**热门、最新（实战包含热门FPS、MOBA、脱机）**</font>游戏。
> 从实战出发，让学员对U3D引擎有深刻理解，不再畏惧Il2Cpp。


## 3. 课程收获：从理论到实践，从入门到精通
> 课程将从正向出发，不仅了解逆向知识，还能了解正向是如何工作的，如何从正来逆，快速去定位需要的逆向点。同时学完教程，你能真正的理解什么是il2Cpp。Unity引擎是如何工作、解析，面对各类型游戏需求该如何定位。 <font color ="#ff0000">**（教程内容均为全网独家）**</font> 以下为收获内容 <font color ="#ff0000">**(以下均有示例、及实战出发并为当前热门游戏)**</font>：
> * 由正转逆的逆向思维
> * 游戏C#(编译后为IL)如何转换成Cpp并彻底了解Il2Cpp。
> * Dump.CS是如何生成的
> * Unity引擎魔改还原能力
> * IDA分析用法
> * MOBA游戏分析能力
> * 脱机协议分析能力
> * Lua类型游戏分析能力
> * BeeByte插件混淆C#还原能力(示例：月光雕刻师CS混淆加密还原)
> * Il2Cpp高级应用
> * Frida高级应用
> * 手游保护基础原理及pass
> * Android调试环境、生产环境注入进程能力
> * 基础数据加密类型算法还原
> * 等等...



    
## 4. 对抗升级：武器库送上！
> 本次课程购买者将附送工具授权。以下为工具介绍:
> * Runtime下dump 输出 Dump.cs il2cpp.h  IDA脚本 [示例视频](https://www.bilibili.com/video/BV15z4y1G7Gv/)
> * U3D 函数堆栈追踪器(UE4版本后续推出)<font color ="#ff0000"></font>[示例视频](https://www.bilibili.com/video/BV1P94y1Y7pX/)
> * 内部定制版frida <font color ="#ff0000">（学员免费）</font>
> * 无痕注入  非内核root下最完美的无痕注入 （所有检测点均pass）
> * libtprt 一键修复工具，包含So修复、global-metdata修复 ，可在PCIl2CppDumper直接使用 （均有源码）

> 注：  <font color ="#ff0000">**以上工具仅限学员内部学习使用，非学员不可使用也无法购买授权,学员非在授权范围内使用，将收回授权。如学员使用本工具造成法律后果由当事人全部承担。若发现工具泄露出去全部收回授权**</font>



## 5. 本次课程你需要什么: 装备自己，准备战斗
> * <font color ="#ff0000">**C语言基础**</font>
> * Root环境手机一部 Pixel4 5 6 为佳
> * 基本的动手能力

> * 注： 因报名后未满足必须项所引起的纠纷一概不进行任何退款
## 6. 课程目录 
### 课程试看
> #### [试看之Il2Cpp源码讲解](https://www.bilibili.com/video/BV1X94y1P7Wh/)
### 课程已正式开始
> ### 一.基础篇
> #### 1.课程概述（已录制）
> #### 2.使用工具（已录制）
> #### 3.Il2Cpp介绍（已录制）
> #### 4.什么是Il2Cpp (已录制）
> #### 5.Dump篇-为什么需要Runtime下Dump(已录制）
> ###  Il2Cpp基础正式开始
> #### 6.Dump篇-初识Dump的3个结构体(1) (已录制 时长20:19）
> #### 6.Dump篇-初识Dump的3个结构体(2) (已录制 时长25:57）
> #### 6.Dump篇-初识Dump的3个结构体(3) (已录制 时长19:50）
> #### 7.Dump篇-Runtime中Dump dll(1) (已录制 时长37:00）
> #### 7.Dump篇-Runtime中Dump dll(2) (已录制 时长37:25 ）
> #### 7.Dump篇-Runtime中Dump dll(3) (已录制 时长31:31 ）
> #### 8.Dump篇-Runtime中Dump 泛型Class，前缀Class ，接口Class 合并（已录制 时长107:00）
> #### 9.Dump篇-Rntimee中Dump Filed Methods （已录制 时长98:00）
> #### 10.Dump篇-什么是Usage及它的使用场景 （已录制 时长105:00）
> #### 11.Dump篇-泛型函数调用表（已录制 时长145:00）
> #### 12.Dump篇-Il2Cpp.h头文件是如何生成的（已录制 时长70:00）
> #### 13-14Dump篇-生成il2cpp.h 和Script.json （已录制 时长 280:00）
> #### 15-Dump篇- 生成IDA脚本完成（时长: 100:00）
> #### 基础篇结束
### 实战篇
> #### 企鹅MOBA魔改引擎还原（1） （时长: 90:00）
> #### 企鹅MOBA魔改引擎还原及字符串解密（2） （时长: 100:00）
> #### 企鹅MOBA数据分析(3)(时长60:00)
> #### 企鹅MOBA信息读取(4)（时长60:00）
> #### 企鹅MOBA搭建读取框架(5) 时长(60:00)
> #### 企鹅MOBA改写读取框架实现免HOOK 读取(100:00)
> #### 企鹅MOBA坐标系统分析读取(100:00)
> #### 企鹅MOBA远程绘制调用(90:00)
> #### 企鹅MOBA 消失的methodInfo还原（随游戏更新）（120:00）
> #### 企鹅MOBA 结束。
> ============================================================
> #### 协议分析篇前瞻 （48:00）
> #### 协议分析之lua游戏的Dump (46:00)
> #### 协议分析之lua游戏的加载区别(44:00)
> #### 协议分析之luaOpCode魔改还原(66:00)
> #### 协议分析之UnLuac魔改还原字节码为lua文件(67:00)
> #### 协议分析之Proto文件Dumpe（60：00）
> #### 协议分析之使用专用堆栈工具动静结合分析组包(46:00)
> #### 协议分析之脱机框架搭建(67:00)
> #### 协议分析之协议登录Socket服务器(71:00)
> #### 协议分析-脱机-HybridCLR游戏的Dump处理 (60:00)
> #### 协议分析-脱机KCP协议框架的搭建(120:00)
> #### 协议分析-脱机协议-登录区服、角色选择、进入游戏(110:00)
> #### 协议分析-中控的实现(35:00)
### 注入篇
> #### 注入的检测及原理应用(60:00)
> #### 无痕注入的原理及检测，无痕Hook原理(60:00)
### 番外篇 
> #### 内核调用绕过保护DumpSo (时长31：00)
> #### 无Hook及Hook 2种方式获取静态变量值(时长47：00)
> ####  某保护之消失的global-metadata(时长37:00);
> #### **热点武侠吃鸡手游YJDump分析(时长39:00) (2024/7/26更新)  PS：完整的数据，纯静态分析实现**;
### 保护篇
> #### 国内保护天花板X盾符号表还原（36:00） (2024/9/14 更新)
> #### libtprt 一键修复工具使用(10:00) (2024/11/9 更新)
> #### Elf文件格式详解 (30:00 ) (2024/11/9 更新)
### 资源篇
> #### 外部加载自定义资源 (60:00)
<img alt ="u3d.ong" src="https://raw.githubusercontent.com/IIIImmmyyy/U3DGameCourse/main/source/u3d.png" >

## 7. 课程答疑
> ### 1. 授课方式更新进度
> ### 课程采用录播授课，为保证授课质量，暂定一周2-3节课程，不定时直播答疑解决问题
> ### 2.课程可以与人合买吗？
> ### 本次课程采用严格的一对一机制，禁止合买，共享。违者封禁授权、并不进行任何退款。
> ### 补充说明： 报名人数满10人及开始授课，且本次课程将限制报名人数、暂定50人。满员后禁止任何形式的报名。



## 8. 课程购买：投资自己，是最好的投资
> ###  U3D手游安全本次教程价格为9999元，且课程的播放需要绑定个人信息并且签署保密协议。后期会根据更新课程的价值提高售价。


## 9. 申明
> ### 1. 视频课课程由于特殊性质，课程一旦发放，不支持任何理由的退款，购买请知晓，同时须知各项注意事宜，报名即默认条款。


## 10.注意事宜
> ### 1.禁止以任何的形式泄露、传播课程视频、源代码
> ### 2.禁止以任何形式泄露课程附属工具
> ### 3.禁止以非学习目的使用附属工具进行违法行为
> ### 违反以上事宜，将按照保密协议，依法追究其法律责任
> ### 最终解释权归本人所有

## 11.联系方式
> ### QQ：295238641
> ### 交流群： 930924631

## 学员学习反馈

> ### <img alt ="feedback1.ong" src="https://raw.githubusercontent.com/IIIImmmyyy/U3DGameCourse/main/source/feedback1.png" >
> ### ======================================================================================================================
> ### <img alt ="feedback2.ong" src="https://raw.githubusercontent.com/IIIImmmyyy/U3DGameCourse/main/source/feedback2.png" >
