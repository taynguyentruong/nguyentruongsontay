---
title: "Bài 5: Xử lý ngoại lệ (Exception Handling) trong Java"
date: 2024-12-22T16:00:00+07:00
draft: false
tags: ["Java", "Exception"]
description: "Cách sử dụng try-catch-finally để xử lý lỗi."
---

Trong Java, Exception là một sự kiện xảy ra trong quá trình thực thi chương trình làm gián đoạn luồng bình thường.

## Khối try-catch
```java
try {
    int data = 50 / 0;
} catch (ArithmeticException e) {
    System.out.println("Lỗi chia cho 0!");
} finally {
    System.out.println("Luôn luôn chạy.");
}
```

Việc xử lý ngoại lệ giúp chương trình không bị crash đột ngột khi gặp lỗi runtime.
