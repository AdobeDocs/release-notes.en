---
cloud: Experience Cloud
type: Documentation
solution: Experience Cloud
role: User,Admin,Developer
product: Experience Cloud
mini-toc-levels: 2
git-repo: https://github.com/AdobeDocs/release-notes.en
index: yes
---

# Metadata for internal use

The metadata.md file includes repo-level metadata that passes through to user guide TOC.md files in the repo. If you want to change metadata.md content for any user guide, do so in any TOC.md file.

| metadata | what it does |
|--- |--- |
| solution-title | Used in article header as link. Keep it short. |
| solution-hub-url | Opens helpx hub page |
| solution-icon | Displays solution icon next to solution title. Not yet implemented |
| getting-started-title | Rarely used when Tutorials is not appropriate |
| getting-started-url | Link to helpx getting started page |
| tutorials-title | Rarely used when Tutorials is not appropriate |
| tutorials-url | Link to video tutorials--either helpx tutorials or KT tutorials |
| mini-toc-levels | Determines the number of heading levels that appear in right rail. default is 2 |
| git-repo | Specifies the location of the collaboration repo. Use the github.com mirror for public-facing docs |

In TOC.md file

| metadata | what it does |
|--- |--- |
| user-guide-title | Used in article header as link |
| user-guide-url | Opens helpx hub page |
