---
title: Welcome to Jeff's Second Brain
index: "false"
---
## What Is This?

My "first brain" gets tired if it thinks about one thing for more than ~5 minutes, which means that the attention required to complete a [full blog post](https://jjacobs.me/blog) is rare. Hence, as a shameless ripoff of Cosma Shalizi's [notebooks](http://bactra.org/notebooks/), here is where I'll post the fleeting thoughts that pop up as I read books and make connections between things 🙈

## Notebook Index

```dataview
TABLE WITHOUT ID link(file.link, choice(title, title, file.aliases[0])) AS "Title", file.mtime AS "Last Updated"
FROM "content"
WHERE index = "true"
SORT file.mtime DESC
```
