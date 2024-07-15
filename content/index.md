---
title: Welcome to Jeff's Second Brain
index: "false"
---
## What Is This?

My "first brain" gets tired if it thinks about one thing for more than ~5 minutes, which means that the attention required to complete a [full blog post](https://jjacobs.me/blog) is rare. Hence, as a shameless ripoff of Cosma Shalizi's [notebooks](http://bactra.org/notebooks/), here is where I'll post the fleeting thoughts that pop up as I read books and make connections between things 🙈

## Notebook Index
<!-- QueryToSerialize: TABLE WITHOUT ID link(replace(title, " ", "_")) AS "Page", file.mtime AS "Last Updated" FROM "content" WHERE index = "true" SORT file.mtime DESC -->
<!-- SerializedQuery: TABLE WITHOUT ID link(replace(title, " ", "_")) AS "Page", file.mtime AS "Last Updated" FROM "content" WHERE index = "true" SORT file.mtime DESC -->

| Page                                                      | Last Updated             |
| --------------------------------------------------------- | ------------------------ |
| [[content/Chechnya.md\|Chechnya]]                         | 12:01 AM - July 15, 2024 |
| [[content/Population_Transfers.md\|Population_Transfers]] | 12:00 AM - July 15, 2024 |
| [[content/Cold_War.md\|Cold_War]]                         | 11:47 PM - July 14, 2024 |
| [[content/Cuba.md\|Cuba]]                                 | 11:30 PM - July 14, 2024 |
| [[content/Russian_Imperialism.md\|Russian_Imperialism]]   | 11:29 PM - July 14, 2024 |
<!-- SerializedQuery END -->

<!-- Dataview (for debugging)
```dataview
TABLE WITHOUT ID file.link AS "Page", file.mtime AS "Last Updated"
FROM "content"
WHERE index = "true"
SORT file.mtime DESC
```
-->

<!-- Old dataview:

```dataview
TABLE WITHOUT ID link(file.link, choice(title, title, file.aliases[0])) AS "Title", file.mtime AS "Last Updated"
FROM "content"
WHERE index = "true"
SORT file.mtime DESC
```

-->