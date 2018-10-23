---
title: Magic Number in Code
date: 2018-10-23 23:11:58
categories:
  - code
tags:
  - effective code
---

Magic number is a number with specific meaning in code.

<!-- more -->

For example:

``` c++
if (200 == status) { // 200 is a magic number
    ...
}
```

``` c++
float new_price = 1.1 * price; // 1.1 is a magic number
```
