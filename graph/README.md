# Graph

## 知识关系图

`knowledge-edges.yml` 描述计算机世界本身的关系。

常用关系：

- `part_of`
- `subtype_of`
- `example_of`
- `uses`
- `manages`
- `executes`
- `executed_by`
- `processes`
- `receives`
- `produces`
- `stores`
- `encodes`
- `encoded_by`
- `communicates_with`
- `depends_on`
- `enables`
- `contrasts_with`
- `often_confused_with`
- `historically_precedes`
- `historically_replaced`
- `influenced`

`subtype_of` 用于“某类概念属于更宽泛类别”，例如 `general-purpose-computer subtype_of computer`。它不同于 `example_of`：前者连接类别，后者连接具体实例或典型例子。

`related_to` 只在暂时没有更精确关系时使用。

## 教学关系图

`learning-edges.yml` 描述怎样学习：

- `prerequisite_for`
- `recommended_before`
- `optional_before`
- `introduced_in`
- `deepened_in`
- `reviewed_in`
- `mentioned_in`
- `included_in_route`

所有非对称关系必须明确方向。
