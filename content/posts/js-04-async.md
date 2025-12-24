---
title: "Bài 9: Bất đồng bộ trong JavaScript (Async/Await)"
date: 2024-12-23T16:00:00+07:00
draft: false
tags: ["JavaScript", "Async"]
description: "Xử lý bất đồng bộ hiện đại với Promise và Async/Await."
---

JavaScript là ngôn ngữ đơn luồng, nhưng xử lý các tác vụ IO (như gọi API) một cách bất đồng bộ.

## Promise
Là một đối tượng đại diện cho một tác vụ chưa hoàn thành.

## Async / Await
Cú pháp "ngọt" (syntactic sugar) giúp viết code bất đồng bộ trông giống đồng bộ.

```javascript
async function fetchData() {
    try {
        const response = await fetch("https://api.example.com/data");
        const data = await response.json();
        console.log(data);
    } catch (error) {
        console.error("Lỗi:", error);
    }
}

fetchData();
```
Đây là cách hiện đại và dễ đọc nhất để xử lý Ajax.
