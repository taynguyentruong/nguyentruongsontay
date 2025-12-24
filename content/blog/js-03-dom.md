---
title: "Bài 8: DOM Manipulation trong JavaScript"
date: 2024-12-23T14:00:00+07:00
draft: false
tags: ["JavaScript", "DOM"]
description: "Tương tác với các phần tử HTML thông qua DOM."
---

DOM (Document Object Model) biểu diễn trang web dưới dạng cây các đối tượng.

## Truy xuất phần tử
```javascript
const btn = document.getElementById("myBtn");
const items = document.querySelectorAll(".item");
```

## Thay đổi nội dung
```javascript
btn.innerText = "Đã click!";
btn.style.backgroundColor = "blue";
```

## Sự kiện (Events)
```javascript
btn.addEventListener("click", () => {
    alert("Button clicked!");
});
```
