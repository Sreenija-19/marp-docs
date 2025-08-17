---
marp: true
title: Product Documentation
author: Sreenija A K
email: 23f1001052@ds.study.iitm.ac.in
theme: custom
paginate: true
---

<!-- _footer: *Page footer: Product Docs* -->
# Product Documentation

Welcome to the technical documentation for our product.

Email: 23f1001052@ds.study.iitm.ac.in

---

<!-- _backgroundColor: #264653 -->
![bg cover](images/product-bg.jpg)

# Product Overview

- High-performance
- Scalable architecture
- Easy-to-use API
- Fully documented

---

<!-- _class: lead -->
# Algorithm Complexity

The sorting algorithm has average complexity:

$$
T(n) = O(n \log n)
$$

Worst-case complexity:

$$
T(n) = O(n^2)
$$

---

<!-- _color: #f4a261 -->
# Example API Usage

```python
def compute_factorial(n):
    if n == 0:
        return 1
    return n * compute_factorial(n-1)

print(compute_factorial(5))
