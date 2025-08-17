---
marp: true
title: Product Documentation
author: Sreenija A K
email: 23f1001052@ds.study.iitm.ac.in
theme: custom
paginate: true
---

<!-- Custom theme -->
<style>
section {
  background: #f5f5f5;
  color: #333;
  font-family: 'Segoe UI', sans-serif;
}
h1, h2 {
  color: #2a9d8f;
}
h3, h4 {
  color: #264653;
}
code {
  background: #e9ecef;
  padding: 2px 4px;
  border-radius: 3px;
}
blockquote {
  font-style: italic;
  color: #6c757d;
}
</style>

# Product Documentation

Welcome to the technical documentation for our product.

Email: 23f1001052@ds.study.iitm.ac.in

---

<!-- Slide with background image -->
![bg cover](images/product-bg.jpg)

# Product Overview

- High-performance
- Scalable architecture
- Easy-to-use API
- Fully documented

---

<!-- Slide with math equation -->
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

<!-- Slide with code -->
# Example API Usage

```python
def compute_factorial(n):
    if n == 0:
        return 1
    return n * compute_factorial(n-1)

print(compute_factorial(5))
