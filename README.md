# stata_graphics
Stata graphics related notes

```
sysuse auto, clear
graph bar price weight length, over(foreign)
```
![bars for each variables over category of foreign](./bar1.svg)

but it's difficult to produce

![bars for category of foreign grouped by each variable](./bar2.svg)
