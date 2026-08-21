# Graph

## 知识关系图

knowledge-edges.yml 描述计算机世界本身的关系。

常用关系：

- part_of
- subtype_of
- example_of
- uses
- manages
- executes
- executed_by
- processes
- receives
- produces
- stores
- encodes
- encoded_by
- communicates_with
- depends_on
- enables
- contrasts_with
- often_confused_with
- historically_precedes
- historically_replaced
- influenced

subtype_of 用于“某类概念属于更宽泛类别”，例如 general-purpose-computer subtype_of computer。它不同于 example_of：前者连接类别，后者连接具体实例或典型例子。

related_to 只在暂时没有更精确关系时使用。

## 教学关系图

learning-edges.yml 描述怎样学习：

- prerequisite_for
- recommended_before
- optional_before
- introduced_in
- deepened_in
- reviewed_in
- mentioned_in
- included_in_route

所有非对称关系必须明确方向。

## 课程关系图

课程关系图描述大学计算机专业知识的组织方式，与知识关系图、文章学习关系图分开维护：

- ../curriculum/domain-map.yml：20 个领域、课程和模块骨架；
- curriculum-edges.yml：课程节点、简单入口和课程之间的关系；
- curriculum-overview.mmd：课程主干的可视化概览。

课程图谱中的关系：

- organized_under：课程属于哪个一级领域；
- prerequisite_for：前者是理解后者的重要前置；
- recommended_before：建议先接触，但不是绝对门槛；
- contextualizes：提供历史、社会或现实背景；
- opens：简单入口可以通向哪些课程。

课程图谱不是唯一阅读顺序。它保留网状知识结构，paths/ 中的路线只是从图谱中选择的可读视图。
