---
id: cpu
type: concept
term: CPU
english: central processing unit
aliases:
  - 中央处理器
  - 处理器
primary_domain: hardware-and-chips
secondary_domains:
  - operating-systems
  - programming
module: cpu-and-instruction-execution
status: drafted
coverage_priority: core
difficulty: beginner
deep_dive_value: high
interest_potential: high
standalone_friendly: true
lookup_friendly: true
systematic_route: true
essence: 从指令流中取出并执行机器指令，同时协调数据移动和系统计算过程的处理器。
common_phrases:
  - CPU 占用很高
  - CPU 核心数
  - CPU 主频
  - CPU 满载
often_confused_with:
  - gpu
  - computer
local_network:
  - hardware
  - program
  - ram
  - instruction
  - operating-system
  - cache
source_refs: []
last_reviewed: null
---

# CPU

## 一句话解释

CPU 是负责读取并执行机器指令的核心处理器。

## 本质压缩

它不断进行取指、译码和执行，并通过寄存器、缓存、内存和其他部件获得或写回数据。

## 它解决什么问题

把程序描述的规则变成实际计算、判断和数据移动。

## 别人通常会怎么说

- “CPU 占用很高”：处理器的大部分可用执行时间正在忙于任务。
- “八核 CPU”：通常表示包含多个可以并行执行任务的处理核心。
- “CPU 满载”：处理器当前可用能力接近被完全使用。

## 一个直觉类比

CPU 像严格执行微小步骤的工作组，程序把复杂任务拆成它能处理的指令。

## 类比的边界

CPU 不独自保存全部数据，也不直接理解“打开网页”这样的高层意图；高层操作会被逐层转换为大量低层指令。

## 容易和什么混淆

CPU 不是整台计算机。GPU 也是处理器，但结构和擅长的任务不同。
