---
title: "Bài 7: Các tính năng mới trong ES6"
date: 2024-12-23T11:00:00+07:00
draft: false
tags: ["JavaScript", "ES6"]
description: "Arrow function, Template literal và Destructuring."
---

ES6 (ECMAScript 2015) mang lại nhiều cải tiến lớn cho JavaScript.

## Arrow Function
Cú pháp ngắn gọn hơn cho hàm.
```javascript
const sum = (a, b) => a + b;
```

## Template Literals
Sử dụng backticks `` ` `` để nội suy chuỗi.
```javascript
let name = "Sơn Tây";
console.log(`Xin chào ${name}`);
```

## Destructuring
Giải nén giá trị từ mảng hoặc đối tượng.
```javascript
const user = { id: 1, name: "Admin" };
const { name } = user;
```
