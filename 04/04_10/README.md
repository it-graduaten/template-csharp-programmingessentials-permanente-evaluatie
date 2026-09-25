# 04_10

Een school wil een systeem bouwen om de resultaten van een examen te bekijken. Er zijn exact vijf studenten die de toets hebben gemaakt.

Gebruik een int-array om de scores op te slaan. Vraag de gebruiker om de score van elke student in te voeren (een geheel getal tussen 0 en 100).

Tonen na het invoeren van alle scores:
- De hoogste score en de naam van de student met de hoogste score (de studentenamen zijn: "Student A", "Student B", "Student C", "Student D", "Student E").
- De laagste score en de naam van de student met de laagste score.
- Het gemiddelde van alle scores.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Description:** Run 1: args=38, 50, 69, 53, 25


**Input:**

```
38
50
69
53
25
```

**Expected Output:**

```
De hoogste score is 69 van Student C.
De laagste score is 25 van Student E.
Het gemiddelde is 47.
```

---

### Case 2

**Description:** Run 2: args=30, 21, 42, 89, 66


**Input:**

```
30
21
42
89
66
```

**Expected Output:**

```
De hoogste score is 89 van Student D.
De laagste score is 21 van Student B.
Het gemiddelde is 49.6.
```

---

### Case 3

**Description:** Run 3: args=49, 86, 67, 29, 20


**Input:**

```
49
86
67
29
20
```

**Expected Output:**

```
De hoogste score is 86 van Student B.
De laagste score is 20 van Student E.
Het gemiddelde is 50.2.
```

---

### Case 4

**Description:** Run 4: args=89, 27, 97, 28, 22


**Input:**

```
89
27
97
28
22
```

**Expected Output:**

```
De hoogste score is 97 van Student C.
De laagste score is 22 van Student E.
Het gemiddelde is 52.6.
```

---

### Case 5

**Description:** Run 5: args=84, 49, 71, 23, 83


**Input:**

```
84
49
71
23
83
```

**Expected Output:**

```
De hoogste score is 84 van Student A.
De laagste score is 23 van Student D.
Het gemiddelde is 62.
```

---

### Case 6

**Description:** Run 6: args=72, 52, 66, 43, 77


**Input:**

```
72
52
66
43
77
```

**Expected Output:**

```
De hoogste score is 77 van Student E.
De laagste score is 43 van Student D.
Het gemiddelde is 62.
```

---

### Case 7

**Description:** Run 7: args=79, 33, 9, 88, 47


**Input:**

```
79
33
9
88
47
```

**Expected Output:**

```
De hoogste score is 88 van Student D.
De laagste score is 9 van Student C.
Het gemiddelde is 51.2.
```

---

### Case 8

**Description:** Run 8: args=23, 72, 92, 11, 73


**Input:**

```
23
72
92
11
73
```

**Expected Output:**

```
De hoogste score is 92 van Student C.
De laagste score is 11 van Student D.
Het gemiddelde is 54.2.
```

---

### Case 9

**Description:** Run 9: args=90, 4, 38, 46, 49


**Input:**

```
90
4
38
46
49
```

**Expected Output:**

```
De hoogste score is 90 van Student A.
De laagste score is 4 van Student B.
Het gemiddelde is 45.4.
```

---

### Case 10

**Description:** Run 10: args=31, 14, 37, 2, 32


**Input:**

```
31
14
37
2
32
```

**Expected Output:**

```
De hoogste score is 37 van Student C.
De laagste score is 2 van Student D.
Het gemiddelde is 23.2.
```

---

### Case 11

**Description:** Run 11: args=65, 70, 20, 91, 90


**Input:**

```
65
70
20
91
90
```

**Expected Output:**

```
De hoogste score is 91 van Student D.
De laagste score is 20 van Student C.
Het gemiddelde is 67.2.
```

---

### Case 12

**Description:** Run 12: args=41, 89, 16, 4, 100


**Input:**

```
41
89
16
4
100
```

**Expected Output:**

```
De hoogste score is 100 van Student E.
De laagste score is 4 van Student D.
Het gemiddelde is 50.
```

---

### Case 13

**Description:** Run 13: args=44, 89, 21, 17, 55


**Input:**

```
44
89
21
17
55
```

**Expected Output:**

```
De hoogste score is 89 van Student B.
De laagste score is 17 van Student D.
Het gemiddelde is 45.2.
```

---

### Case 14

**Description:** Run 14: args=85, 55, 35, 0, 15


**Input:**

```
85
55
35
0
15
```

**Expected Output:**

```
De hoogste score is 85 van Student A.
De laagste score is 0 van Student D.
Het gemiddelde is 38.
```

---

### Case 15

**Description:** Run 15: args=75, 20, 9, 94, 78


**Input:**

```
75
20
9
94
78
```

**Expected Output:**

```
De hoogste score is 94 van Student D.
De laagste score is 9 van Student C.
Het gemiddelde is 55.2.
```

---
