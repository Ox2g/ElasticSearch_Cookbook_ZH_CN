## Search, Queries,  and Filters 搜索、查询和过滤

本章节中，我们主要讲述以下内容

- 执行一个查询
- 排序结果
- 高亮结果
- 执行一个扫描查询
- 提供正确查询建议
- 计算匹配结果数量
- 根据查询结果删除文档
- 匹配全部文档
- 基于单个准确值的查询和过滤
- 基于多个准确值的查询和过滤
- 使用前缀的查询和过滤
- 使用布尔的查询和过滤
- 使用范围的查询和过滤
- Using span queries
- 使用匹配查询
- 使用ID的查询和过滤
- 使用has_child的查询和过滤
- 使用top_children的查询和过滤
- 使用has_parent的查询和过滤
- 使用正则表达式的查询和过滤
- 使用自定义分数的查询
- 使用存在和丢失的过滤
- 使用 and/or/not 的过滤
- Using a geo bounding box filter
- 使用geo多边形过滤
- 使用geo距离过滤
- 使用QueryString查询
- 使用模板查询

## 介绍

在你已经设置完映射并把数据放入索引之后，你可以开始搜索了。在本章节，我们将讲述不同类型的搜索查询和过滤器、确认查询(validating queries)、高亮搜索结果和限定的字段。本章节是全书的核心：基本上，ElasticSearch中的每件事都是为了提供查询和返回高质量的结果而服务的。为了精通ElasticSearch，用户必须明白一个查询和一个过滤器、如何提高查询质量和如何设计更高效的查询。ElasticSearch允许你使用丰富的领域声明语言(DSL)，DSL是一个专门为搜索设计的语法语言，可以完成从普通的单元查询到复杂的地图图形拦截器的全部需求。

本章节总共分为两部分：第一部分展示了搜索相关的一些API，第二部分则详细讲述了QueryDSL的查询语法。

在开始之前，需要你准备和填充需要的索引。在[PacktPub](https://www.packtpub.com/big-data-and-business-intelligence/elasticsearch-cookbook)和[Github](https://github.com/aparo/elasticsearch-cookbook-second-edition)上可以找到数据初始化的脚本来初始化全部的数据。
