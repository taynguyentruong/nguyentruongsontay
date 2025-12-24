---
title: "Bài 4: Java Stream API"
date: 2024-12-22T14:00:00+07:00
draft: false
tags: ["Java", "Stream"]
description: "Xử lý dữ liệu hiệu quả với Stream API trong Java 8."
---

Stream API được giới thiệu trong Java 8 giúp xử lý các collection theo phong cách functional.

```java
List<Integer> numbers = Arrays.asList(1, 2, 3, 4, 5, 6);
List<Integer> evenNumbers = numbers.stream()
    .filter(n -> n % 2 == 0)
    .collect(Collectors.toList());

System.out.println(evenNumbers); // [2, 4, 6]
```
Stream giúp code ngắn gọn và dễ đọc hơn rất nhiều so với vòng lặp `for` truyền thống.
