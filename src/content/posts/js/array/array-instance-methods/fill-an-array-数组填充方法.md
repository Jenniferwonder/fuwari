---
Datereviewed: 2024-01-26
aliases:
  - Fill an Array-数组填充方法
title: Fill an Array-数组填充方法
topic:
  - Array
type: D
tags:
  - JavaScript
DateStarted: 2024-01-26
DateModified: 2024-04-18
reviewed: 1
difficulty: Good
status: 
comment: 
linter-yaml-title-alias: Fill an Array-数组填充方法
category: Programming
---

# Fill an Array-数组填充方法

---

Basic

### Fill the entire array with value 5

Back:

- `.fill(5)`
- ![](https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/programming/1691292422220.png)
- ![](https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/programming/1691292315495.png)  
📌: JS::JS-Array  
🏷️: JS-Array
<!--ID: 1706600287356-->

---

<!--SR:!2024-02-01,3,250-->

---

Basic

### Fill all indices >=3 with 6

Back:

- `.fill(6,3)`
- ![](https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/programming/1691292351811.png)
<!--ID: 1706600287359-->

---

<!--SR:!2024-02-01,3,250-->

---

Basic

### Fill all indices >= 1 and < 3 with 7

Back:

- `.fill(7,1,3)`
- ![](https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/programming/1691292362365.png)
<!--ID: 1706600287362-->

---

<!--SR:!2024-02-01,3,250-->

---

Basic

### Meaning of `[0,0,0,0,0].fill(8,-4,-1)`

Back:

- Fill all indices >=1 and < 4 with 8
- ![](https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/programming/1691292373703.png)
<!--ID: 1706600287366-->

---

<!--SR:!2024-02-01,3,250-->

---

Basic

### Avoid Invalid Fill Value

Back:

- // Fill with **too low indices** is noop
  - ![](https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/programming/1691292459859.png)
- // Fill with **too high indices** is noop
  - ![](https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/programming/1691292467153.png)
- // Fill with **reversed indices** is noop
  - ![](https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/programming/1691292480812.png)
- // Fill with **partial index overlap** is best effort - ![](https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/programming/1691292489788.png)
<!--ID: 1706600287369-->

---

<!--SR:!2024-02-01,3,250-->
