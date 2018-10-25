---
title: Magic Number in Code
date: 2018-10-23 23:11:58
categories:
  - code
tags:
  - effective code
---

`Magic number` is a number with specific meaning in code.

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

When we are coding, we know exact meaning of `magic number`. But when other people in our team reading the code with `magic number`, they will be confused about these numbers.



 I'm pretty sure that we will forget the meaning of these numbers long after our code done.

Someone may suggest that we can use `comment` to solve this problem. For Example:

``` c++
if (200 == status) { // 200 means HTTP OK
    ...
}
```
