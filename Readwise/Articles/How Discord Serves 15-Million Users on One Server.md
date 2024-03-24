---
Type: articles
tags:
  - Readwise
Author: Dev Notes 🖥️
Processed: false
URL: 
Related: 
owner: Tanzeel159
repo: Digital-Garden-content
attachment: true
dataview: false
share: true
date created: 2024-01-19 03:13:02
date modified: 2024-03-24 10:03:51
---
![rw-book-cover](https://readwise-assets.s3.amazonaws.com/static/images/article0.00998d930354.png)

## Highlights
- Discord, the popular communication platform, has achieved a remarkable feat by expanding the capacity of a single server to support 15 million users, a significant leap from the previous limit of around 1 million users. ([View Highlight](https://read.readwise.io/read/01hmgdh4cg0d1dsp0ngpdsxyyh))
- The challenge began when the Midjourney server's growth threatened to surpass Discord's established user limit per server. ([View Highlight](https://read.readwise.io/read/01hmgdh7zhr2yazfpjhcjy3der))
- One of the critical issues encountered was a performance drop due to pathological garbage collection, which occurred when freeing small memory allocations outside the heap. The solution was to tune the virtual binary heap size, which allowed for the enabling of offload and significantly improved throughput. ([View Highlight](https://read.readwise.io/read/01hmgdhgm0dyhfk575587f2hjp))
    - Note: When Discord was serving a lot of people, they noticed that the computer was slowing down when it tried to get rid of small pieces of memory. They fixed this problem by changing how much memory the computer used and it made things faster.
