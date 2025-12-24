---
title: "Bài 2: Các khái niệm cơ bản của OOP trong Java"
date: 2024-12-21T10:00:00+07:00
draft: false
tags: ["Java", "OOP"]
description: "Tìm hiểu 4 tính chất của Lập trình hướng đối tượng trong Java."
---

Lập trình hướng đối tượng (OOP) là nền tảng của Java. Có 4 tính chất chính:

1. **Tính đóng gói (Encapsulation)**: Che giấu dữ liệu bên trong class.
2. **Tính kế thừa (Inheritance)**: Class con kế thừa thuộc tính và phương thức của class cha.
3. **Tính đa hình (Polymorphism)**: Một phương thức có thể có nhiều cách thực hiện khác nhau.
4. **Tính trừu tượng (Abstraction)**: Ẩn đi chi tiết triển khai, chỉ hiển thị tính năng.

```java
class Animal {
    void makeSound() {
        System.out.println("Some sound...");
    }
}

class Dog extends Animal {
    @Override
    void makeSound() {
        System.out.println("Gâu gâu");
    }
}
```
