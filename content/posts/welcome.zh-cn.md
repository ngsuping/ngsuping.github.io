---
title: "你好，欢迎"
date: 2026-05-13
summary: "建站说明 & 内容规划"
tags: ["杂谈"]
---

这里是我的个人作品集网站。

主要内容分两块：

1. **[项目](/projects/)**：我做过的数据分析 / 商业分析项目案例
2. **[笔记](/posts/)**：数据分析 + AI 学习笔记，以及面试经验

笔记按"系列（playlist）"组织，目前有三个系列：

- [数据分析](/series/data-analysis/) — SQL / Python / 业务分析
- [AI for Everyone](/series/ai-for-everyone/) — 给非技术背景的人讲 AI
- [AI + 数据分析](/series/ai-data-analysis/) — 把 AI 工具用进数据分析日常

我的简历在 [关于](/about/) 页面。

---

## 怎么把一篇文章加进某个系列？

在文章顶部 frontmatter 里加 `series` 字段即可：

```yaml
---
title: "我的第一篇 SQL 笔记"
date: 2026-05-15
series: ["data-analysis"]    # 系列 slug（参考 content/series/ 下的文件夹名）
series_order: 1               # 在系列里的顺序
tags: ["SQL"]
---
```

同系列的文章会自动串成一个 playlist，文末有上一篇/下一篇导航。
