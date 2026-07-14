---
id: special-purpose-computer
type: concept
term: 专用计算机
english: special-purpose computer
aliases:
  - 专用计算设备
  - 专用控制器
primary_domain: foundations
secondary_domains:
  - hardware-and-chips
  - mobile-embedded-and-control
module: what-is-a-computer
status: drafted
coverage_priority: core
difficulty: beginner
deep_dive_value: high
interest_potential: high
standalone_friendly: true
lookup_friendly: true
systematic_route: true
essence: 围绕有限任务和明确使用环境设计，重点优化特定功能而非自由承担各种任务的计算机。
common_phrases:
  - 专用计算机
  - 专用控制器
  - 嵌入式控制器
  - 这个设备只能做固定任务
often_confused_with:
  - general-purpose-computer
  - fixed-function-circuit
local_network:
  - computer
  - program
  - firmware
  - embedded-system
  - sensor
  - actuator
  - general-purpose-computer
source_refs:
  - source-what-counts-as-a-computer
last_reviewed: null
---

# 专用计算机

## 一句话解释

专用计算机主要为了有限的一类任务而设计，例如控制路由器、家电、汽车部件或工业设备。

## 本质压缩

它仍然按照规则处理输入、保存状态并产生输出，但任务范围通常比个人电脑和手机窄，硬件和软件也更围绕特定目标优化。

## 它解决什么问题

很多设备不需要运行办公软件、游戏和浏览器，只需要可靠、低功耗、低成本地完成某项工作。专用计算机可以减少不必要的功能，并针对现实环境进行设计。

## 通常在哪里听到

路由器、汽车控制单元、智能家电、工业控制器、摄像头、机器人和传感设备中，都可能存在专用计算机。

## 别人通常会怎么说

- “这里面有个控制器”：通常指负责读取输入并控制设备动作的小型计算系统。
- “这是嵌入式设备”：计算机被放进另一件产品中，成为它的一部分。
- “它只能做固定任务”：它的程序和硬件主要为有限功能设计，并不强调用户自由安装软件。

## 一个直觉类比

可以把专用计算机想成一支为特定岗位训练的专业小组。它不负责处理所有工作，但可以把自己的任务做得稳定、节能而且成本较低。

## 类比的边界

专用不等于完全不能改程序。很多专用计算机会运行固件，也可以更新；某些设备还能增加扩展功能。它们与通用计算机之间更像连续光谱，而不是绝对二分。

## 容易和什么混淆

并非所有能够自动工作的装置都是计算机。机械定时器或简单模拟控制电路也能自动运行，但不一定包含现代数字计算系统。

“专用计算机”和“嵌入式系统”也不是完全同义。嵌入式系统强调计算系统被嵌入另一件产品中；专用计算机强调用途范围较集中，两者经常重合。

## 局部网络

- `computer`：专用计算机属于计算机的一类；
- `program`：它可能运行固定或可更新的程序；
- `firmware`：许多专用设备把长期运行的软件称为固件；
- `embedded-system`：专用计算机经常作为其他产品的一部分；
- `sensor`：提供环境和设备状态输入；
- `actuator`：把计算结果转化为现实动作；
- `general-purpose-computer`：用途更广、强调通过不同程序承担多种任务。

## 日常理解到哪里就够了

知道“没有显示器、不能随意安装 App，也可能是一台计算机”，并理解它主要服务于有限任务，就已经足够。

## 相关科普文章

- [到底什么才算一台计算机？](../articles/01-foundations/what-counts-as-a-computer.md)
