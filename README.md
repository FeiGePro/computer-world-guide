# 计算机世界说明书

面向非计算机专业读者的长期计算机通识项目。

本项目同时维护四类对象：

- **科普文章 Article**：围绕现实问题组织解释，负责把知识讲明白；
- **概念节点 Concept**：保存稳定定义、常见说法、易混淆项和局部知识网络；
- **学习路线 Path**：为不同目标安排阅读顺序，不复制正文；
- **知识图谱 Graph**：分别记录知识本身的关系和教学关系。

> 知识地图追求广阔，单篇内容追求完整；深度不由“是不是普通人”决定，而由理解价值、兴趣、逻辑结构和实际反馈决定。

## 从这里开始

第一篇文章：

- [到底什么才算一台计算机？](articles/01-foundations/what-counts-as-a-computer.md)

这篇文章从手机、路由器、家电和汽车控制器等现实例子出发，建立计算机、硬件、软件、程序、数据、输入和输出之间的第一层关系。

## 当前状态

- 架构版本：`v0.15`
- 仓库阶段：`v0.2 content development`
- 正式文章：1 篇初稿
- 概念节点：14
- 实际发送记录：0

详细状态见 [`state/PROJECT_STATUS.md`](state/PROJECT_STATUS.md)。

## 快速入口

- [第一篇文章](articles/01-foundations/what-counts-as-a-computer.md)
- [总体架构](ARCHITECTURE.md)
- [路线图](ROADMAP.md)
- [术语索引](GLOSSARY.md)
- [表达规范](STYLE_GUIDE.md)
- [事实核验规范](FACT_CHECKING.md)
- [轻松零基础路线](paths/easy-beginner.md)
- [系统通识路线](paths/systematic-literacy.md)
- [术语查询路线](paths/terminology-lookup.md)
- [下一批候选主题](state/NEXT_CANDIDATES.md)

## 仓库结构

```text
articles/   面向阅读的正式文章
concepts/   稳定概念节点与术语查询页
paths/      学习路线，只组织入口
sessions/   实际发送和交流记录
graph/      知识关系图与教学关系图
feedback/   兴趣、困难、误解与修订反馈
sources/    可追溯资料来源
templates/  文章、概念和发送记录模板
state/      当前状态与下一步候选
```

## 初期工作流

1. 从 `state/NEXT_CANDIDATES.md` 选择一个主题；
2. 使用 `templates/article.md` 创建文章；
3. 创建或补充文章涉及的概念节点；
4. 更新 `graph/knowledge-edges.yml` 和 `graph/learning-edges.yml`；
5. 技术检查通过后，再决定是否发送；
6. 实际发送后，用 `templates/session.md` 记录反馈。

当前阶段不引入复杂脚本、自动生成器或多人协作规范。达到明确规模后再升级，详见 [`ROADMAP.md`](ROADMAP.md)。
