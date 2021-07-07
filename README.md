# New-material-knowledgeGraph
## 图谱简介
本文所采用知识图谱的数据均从爱化学网站爬取，总共筛选出超过七万条包含中文名以及生产信息的数据，并存储到Neo4j中。效果如下图所示。
![](https://github.com/TCTC00D/New-material-knowledgeGraph/blob/main/graph.png)  
## 使用说明
1、在Neo4j中安装apoc插件。<br>
2、运行命令
  call apoc.cypher.runFile("cyp",{})
