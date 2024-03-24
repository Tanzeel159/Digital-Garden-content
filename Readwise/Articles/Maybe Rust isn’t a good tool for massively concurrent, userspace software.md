---
Type: articles
tags:
  - Readwise
Author: mrkline
Processed: false
URL: https://bitbashing.io/async-rust.html
Related: 
owner: Tanzeel159
repo: Digital-Garden-content
attachment: true
dataview: false
share: true
date created: 2024-02-04 12:06:34
date modified: 2024-03-24 10:04:13
---
![rw-book-cover](https://news.ycombinator.com/favicon.ico)

## Highlights
- **Parallelism** is about running code *in parallel* on several CPUs. ([View Highlight](https://read.readwise.io/read/01ha1483pn7az5crns04y9mea3))
- **Concurrency** is about breaking a problem into separate, independent parts. ([View Highlight](https://read.readwise.io/read/01ha1487bkhm7vxvnjhrst3e1h))
- One of the simplest ways to build a concurrent system is to split code into multiple processes. ([View Highlight](https://read.readwise.io/read/01ha14ak831sg79qrt3sk0pty8))
- ![](https://cube-drone.com/103.gif) ([View Highlight](https://read.readwise.io/read/01ha149kcnypa8jt4hsmctstyg))
- this approach has its limitations. Inter-process communication is not cheap, since most implementations copy data to OS memory and back. ([View Highlight](https://read.readwise.io/read/01ha14b3ywnbqqrt69yt64agkm))
- Some people, when confronted with a problem, think, “I know, I’ll use threads,” and then they have two problems. 
  – Ned Batchelder ([View Highlight](https://read.readwise.io/read/01ha14bfffmtmysh6q0k4c3mcd))
- Communicating Sequential Processes ([View Highlight](https://read.readwise.io/read/01ha14ekafp8vd107km68krqtv))
- Threads enjoy process-like isolation from the rest of the program, since they don’t share memory. ([View Highlight](https://read.readwise.io/read/01ha14esk4h3tb44g0n3n96gzf))
- Each thread has a very obvious set of inputs (the channels it receives from) and outputs (the channels it sends to). ([View Highlight](https://read.readwise.io/read/01ha14f20z9m5a5t4r7yk98nbr))
- Channels *are the synchronization*. If a channel is empty, the receiver waits until it’s not. If a channel is full, the sender waits. Threads never sleep while they have work to do, and gracefully pause if they outpace the rest of the system. ([View Highlight](https://read.readwise.io/read/01ha14fa7q8sz3kmz149hew8md))
