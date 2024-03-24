---
Type: articles
tags:
  - Readwise
Author: sathishmanohar
Processed: false
URL: https://dougseven.com/2014/04/17/knightmare-a-devops-cautionary-tale/
Related: 
owner: Tanzeel159
repo: Digital-Garden-content
attachment: true
dataview: false
share: true
date created: 2024-02-04 12:06:34
date modified: 2024-03-24 10:04:10
---
![rw-book-cover](https://dougseven.files.wordpress.com/2014/04/120806_knight_capital_2.jpg)

## Highlights
- Knight’s Electronic Trading Group (ETG) managed an average daily trading volume of more than 3.3 billion trades daily, trading over 21 billion dollars…daily. That’s no joke! ([View Highlight](https://read.readwise.io/read/01ha134gt38e9hg68zq919rrqn))
- On July 31, 2012 Knight had approximately $365 million in cash and equivalents. ([View Highlight](https://read.readwise.io/read/01ha134kxhcj9rtw6zznh9d25f))
- One of the core functions of SMARS is to receive orders from other components of Knights trading platform (“parent” orders) and then send one or more “child” orders out for execution. ([View Highlight](https://read.readwise.io/read/01ha135yz27yp7z66xnb8gde3r))
- The larger the parent order, the more child orders would be generated. ([View Highlight](https://read.readwise.io/read/01ha13632mqjy9hf5ptxtwysh5))
- one of Knight’s technicians did not copy the new code to one of the eight SMARS computer servers. ([View Highlight](https://read.readwise.io/read/01ha138gw4n6n98jrkwnrc59wk))
- Orders sent to the eighth server triggered the supposable repurposed flag and brought back from the dead the old Power Peg code. ([View Highlight](https://read.readwise.io/read/01ha1395ktwphbgwz9vrdh98gb))
- Basically, Power Peg would keep track of the child orders and stop them once the parent order was completed. ([View Highlight](https://read.readwise.io/read/01ha13dnd8j8rsb05xkdgewhd9))
- When the Power Peg flag on the eighth server was activated the Power Peg functionality began routing child orders for execution, but wasn’t tracking the amount of shares against the parent order – somewhat like an endless loop. ([View Highlight](https://read.readwise.io/read/01ha13e0cwy5en6hwd6yyf27e2))
- Knight’s executions constituted more than 50% of the trading volume, driving certain stocks up over 10% of their value. ([View Highlight](https://read.readwise.io/read/01ha13fy8vpjexpgyn60mt2ara))
- There was no kill-switch (and no documented procedures for how to react) so they were left trying to diagnose the issue in a live trading environment where 8 million shares were being traded every minute . ([View Highlight](https://read.readwise.io/read/01ha13j0jgkw50kagd6sdw8qzv))
- they reacted by uninstalling the new code from the servers it was deployed to correctly. ([View Highlight](https://read.readwise.io/read/01ha13j8jrc935s2ssee90pjyg))
- In other words, they removed the working code and left the broken code. ([View Highlight](https://read.readwise.io/read/01ha13jdvfdy0mzkdkhjdxqfbm))
    - Note: This only amplified the issue, all servers triggered the flag in the code
- In 45-minutes Knight went from being the largest trader in US equities and a major market maker in the NYSE and NASDAQ to bankrupt. ([View Highlight](https://read.readwise.io/read/01ha13nwf7tpnmep2pmkwabp0j))
- It is not enough to build great software and test it; you also have to ensure it is delivered to market correctly so that your customers get the value you are delivering ([View Highlight](https://read.readwise.io/read/01ha13pny4xx5cbhqbkykpgme5))
- Any time your deployment process relies on humans reading and following instructions you are exposing yourself to risk. ([View Highlight](https://read.readwise.io/read/01ha13qfprfc6bcmhd7pfy8p4c))
- Deployments need to be automated and repeatable and as free from potential human error as possible. ([View Highlight](https://read.readwise.io/read/01ha13qzn7qn9z5fpzwa742s8t))
- principles for Continuous Delivery apply here ([View Highlight](https://read.readwise.io/read/01ha13rnyqdch24e96n9c0shm5))
- • Releasing software should be a repeatable, reliable process.
  • Automate as much as is reasonable. ([View Highlight](https://read.readwise.io/read/01ha13rszxgjay87zqxv192x3y))
