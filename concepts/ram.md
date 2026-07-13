---
id: ram
type: concept
term: 内存
english: random-access memory
aliases:
  - RAM
  - 运行内存
primary_domain: hardware-and-chips
secondary_domains:
  - operating-systems
  - mobile-embedded-and-control
module: memory-system
status: drafted
coverage_priority: core
difficulty: beginner
deep_dive_value: high
interest_potential: high
standalone_friendly: true
lookup_friendly: true
systematic_route: true
essence: 为正在运行的程序和系统状态提供高速、可随机访问、通常易失的工作存储空间。
common_phrases:
  - 内存占用太高
  - 软件很吃内存
  - 内存不够了
  - 加一根内存条
  - 内存泄漏
often_confused_with:
  - persistent-storage
  - cache
local_network:
  - cpu
  - operating-system
  - program
  - persistent-storage
  - virtual-memory
  - process
source_refs: []
last_reviewed: null
---

# 内存

## 一句话解释

内存是程序运行时使用的高速临时工作空间，通常断电后不会继续保存其中内容。

## 本质压缩

CPU 需要比长期存储更快的地方放置当前正在使用的代码、数据和状态，RAM 承担了主要工作区角色。

## 别人通常会怎么说

- “内存占用太高”：正在运行的程序和系统占用了较多 RAM。
- “软件很吃内存”：这个软件运行时需要较大的内存空间。
- “加一根内存条”：增加电脑可用的物理 RAM 容量。
- “内存泄漏”：程序不再需要某些内存，却没有正确释放，导致占用持续增长。

## 一个直觉类比

可以把内存想成工作台：当前要处理的东西摆在上面，长期保存的东西则放在仓库。

## 类比的边界

内存地址、缓存、分页和虚拟内存都比工作台复杂；数据也不是真的按“文件物品”整齐摆放。

## 容易和什么混淆

手机宣传中的“8GB+256GB”通常分别表示运行内存和持久化存储空间。

## 日常理解到哪里就够了

知道内存影响同时运行和当前工作的空间，存储空间负责长期保存，就足以处理大多数日常讨论。
