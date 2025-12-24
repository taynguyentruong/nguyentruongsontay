---
title: "Bài 3: Sử dụng Java Collections Framework"
date: 2024-12-22T08:00:00+07:00
draft: false
tags: ["Java", "Collections"]
description: "Hướng dẫn sử dụng List, Set, Map trong Java."
---

Java Collections Framework cung cấp các cấu trúc dữ liệu mạnh mẽ.

## List
List lưu trữ các phần tử theo thứ tự và có thể lặp lại.
```java
List<String> list = new ArrayList<>();
list.add("Java");
list.add("Python");
```

## Set
Set lưu trữ các phần tử không trùng lặp.
```java
Set<String> set = new HashSet<>();
set.add("A");
set.add("A"); // Bỏ qua
```

## Map
Map lưu trữ dữ liệu dưới dạng Key-Value.
```java
Map<String, Integer> map = new HashMap<>();
map.put("One", 1);
```
