# 医疗数据周刊：第1期

记录每周值得分享的医疗数据科学资讯，周六发布。

欢迎投稿推荐，请[提交issue](https://github.com/youcc/weekly-cn/issues)。

微信不允许外部链接，请点击页末左下角的“**阅读原文**”访问文中链接。

![](https://hrdag.org/wp-content/uploads/2016/06/snhr-tree.png)

题图：Patrick Ball的数据项目树状文档

## 文章

1、[Patrick Ball's talk on building workflow](https://hrdag.org/2016/06/14/the-task-is-a-quantum-of-workflow/)

从Patrick Ball的博客中我学习了如何管理数据科学项目资料，比如代码，原始数据，结果报表等等，让你的结果可以成功复制。假如过几个月或一年，我需要回头查看这个项目时，能迅速了解当初怎么分析的，怎么得到同样的结果，当时有哪些重点代码标注等。我目前项目文档树形结构如下：  
- src  - 代码
- docs  - 与原始数据相关文档
- input  - 原始数据
- output  - 结果，比如报表，图片等
- note   - RMarkdown 文档, Jupyter Notebook 等

2、 [A Quick Guide to Organizing Data Science Projects](https://medium.com/outlier-bio-blog/a-quick-guide-to-organizing-data-science-projects-updated-for-2016-4cbb1e6dac71)

该博客介绍了如何管理你的数据科学项目，让你的项目可以成功复制。推荐工具如下：
- 版本控制系统 （git）
- 流程管理工具 （Make, Snakemake, or Luigi)
- 应用部署工具 （Docker）
- 采用web应用来分享你的数据分析结果 （Jupyter Notebook or RMarkdown)
