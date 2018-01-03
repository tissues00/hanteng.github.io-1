---
layout: article
title:  "有道云markdown练习"
date:   2018-1-3 20:27:50 +0800
categories: posts markdown
image:
  feature: markdown.jpg
  teaser: markdown.jpg
---

### To-do List

- [x] 已完成项目1
  - [x] 已完成事项1 
  - [x] 已完成事项2
 - [ ] 待办事项1
 - [ ] 待办事项2
 

#### 流程图
###### 自上而下的顺序

```
graph TB
A-->B
```

###### 自下而上的顺序
```
graph BT
A-->B
```

###### 从左到右的顺序
```
graph LR
A-->B
```

###### 从右到左的顺序
```
graph RL
A-->B
```

#### 流程图

```
graph TD
    A[christmas] -->B(Go shopping)
    B -->C{Let me think}
    C -->|One| D[Laptop]
    C -->|Two| E[iPhone]
    C -->|Three| F[Car]
```

```
gantt
dateFormat YYYY-MM-DD
title 产品计划表
section 初期计划
明确需求: 2016-03-01, 10d
section 中期阶段
跟进开发: 2016-03-11, 15d
section 后期阶段
走查测试: 2016-03-20, 9d
```
