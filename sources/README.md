# Sources

保存项目内部可追溯来源。轻量正文不必展示完整引用，但重要事实必须能够回到这里核验。

建议每条来源记录：

```yaml
id: source-id
title: 标题
author_or_org: 作者或机构
type: official-doc | standard | textbook | paper | museum | archive | technical-reference
url: 可选
published: 可选
accessed: YYYY-MM-DD
supports:
  - article-or-concept-id
notes: 使用范围、争议或限制
```

历史来源放入 `sources/history/`，但历史正文只放在 `articles/02-history/`，避免职责重复。
