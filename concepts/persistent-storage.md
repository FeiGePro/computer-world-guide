---
id: persistent-storage
type: concept
term: 持久化存储
english: persistent storage
aliases:
  - 存储空间
  - 长期存储
primary_domain: hardware-and-chips
secondary_domains:
  - files-and-media
  - mobile-embedded-and-control
module: persistent-storage
status: drafted
coverage_priority: core
difficulty: beginner
deep_dive_value: medium
interest_potential: high
standalone_friendly: true
lookup_friendly: true
systematic_route: true
essence: 在设备断电或程序退出后仍能长期保存程序、文件和其他数据的存储介质与机制。
common_phrases:
  - 存储空间不足
  - 硬盘满了
  - 手机容量
  - 清理存储
often_confused_with:
  - ram
  - cloud-storage
local_network:
  - file
  - ram
  - ssd
  - hdd
  - file-system
  - backup
source_refs: []
last_reviewed: null
---

# 持久化存储

## 一句话解释

持久化存储负责长期保存程序和文件，即使设备关机，内容通常仍然存在。

## 本质压缩

它用较慢但容量更大、断电后可保留内容的介质，承担长期记录功能。

## 别人通常会怎么说

- “存储空间不足”：设备没有足够空间继续保存应用、照片或其他数据。
- “硬盘满了”：长期存储可用容量接近耗尽。
- “手机 256GB”：通常指内置闪存的标称存储容量，而不是运行内存。

## 一个直觉类比

持久化存储像仓库，内存像工作台。

## 类比的边界

现代系统会使用缓存、虚拟内存和存储控制器，仓库与工作台之间并不是简单地整件搬运。

## 容易和什么混淆

云存储最终也依赖远端真实设备保存数据，只是设备不在本地。
