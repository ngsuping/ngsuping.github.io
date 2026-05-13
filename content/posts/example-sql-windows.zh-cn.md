---
title: "[示例] SQL 窗口函数入门"
date: 2026-05-13
summary: "示例文章 —— 演示如何把一篇笔记归入「数据分析」系列"
series: ["data-analysis"]
series_order: 1
tags: ["SQL", "示例"]
draft: false
---

> 这是一篇示例文章。把它替换成你真正的笔记内容即可，或者直接删掉。

## 一句话总结

窗口函数是 SQL 里被严重低估的能力 —— 一旦学会 `OVER(PARTITION BY ... ORDER BY ...)`，很多需要嵌套子查询的场景就能一行搞定。

## 接下来会写什么

- `ROW_NUMBER / RANK / DENSE_RANK` 的区别
- `LAG / LEAD` 跨行计算
- 留存率、累计 GMV 这类常见业务问题的窗口函数解法
