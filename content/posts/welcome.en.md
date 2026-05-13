---
title: "Hello, welcome"
date: 2026-05-13
summary: "About this site & what I'll be sharing"
tags: ["meta"]
---

This is my personal portfolio site.

Two main sections:

1. **[Projects](/en/projects/)** — data and business analysis case studies
2. **[Notes](/en/posts/)** — data analysis + AI learning notes, plus interview prep

Notes are organized as **series** (think YouTube playlists). Three series so far:

- [Data Analysis](/en/series/data-analysis/) — SQL / Python / business analysis
- [AI for Everyone](/en/series/ai-for-everyone/) — AI for non-technical readers
- [AI + Data Analysis](/en/series/ai-data-analysis/) — bringing AI into daily data work

My resume lives on the [About](/en/about/) page.

---

## How to add a post to a series

Add a `series` field in the post's frontmatter:

```yaml
---
title: "My first SQL note"
date: 2026-05-15
series: ["data-analysis"]    # series slug (matches folder under content/series/)
series_order: 1               # position within the series
tags: ["SQL"]
---
```

Posts in the same series get auto-linked with prev/next navigation at the bottom.
