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

**Complete console output:**

```
Geef score van Student A: 48
Geef score van Student B: 33
Geef score van Student C: 60
Geef score van Student D: 39
Geef score van Student E: 35
De hoogste score is 60 van Student C.
De laagste score is 33 van Student B.
Het gemiddelde is 43.
```

**Input:**

```
48
33
60
39
35
```

**Expected Output:**

```
De hoogste score is 60 van Student C.
De laagste score is 33 van Student B.
Het gemiddelde is 43.
```

---

### Case 2

**Complete console output:**

```
Geef score van Student A: 26
Geef score van Student B: 11
Geef score van Student C: 39
Geef score van Student D: 87
Geef score van Student E: 98
De hoogste score is 98 van Student E.
De laagste score is 11 van Student B.
Het gemiddelde is 52.2.
```

**Input:**

```
26
11
39
87
98
```

**Expected Output:**

```
De hoogste score is 98 van Student E.
De laagste score is 11 van Student B.
Het gemiddelde is 52.2.
```

---

### Case 3

**Complete console output:**

```
Geef score van Student A: 47
Geef score van Student B: 93
Geef score van Student C: 92
Geef score van Student D: 0
Geef score van Student E: 43
De hoogste score is 93 van Student B.
De laagste score is 0 van Student D.
Het gemiddelde is 55.
```

**Input:**

```
47
93
92
0
43
```

**Expected Output:**

```
De hoogste score is 93 van Student B.
De laagste score is 0 van Student D.
Het gemiddelde is 55.
```

---

### Case 4

**Complete console output:**

```
Geef score van Student A: 41
Geef score van Student B: 20
Geef score van Student C: 53
Geef score van Student D: 96
Geef score van Student E: 98
De hoogste score is 98 van Student E.
De laagste score is 20 van Student B.
Het gemiddelde is 61.6.
```

**Input:**

```
41
20
53
96
98
```

**Expected Output:**

```
De hoogste score is 98 van Student E.
De laagste score is 20 van Student B.
Het gemiddelde is 61.6.
```

---

### Case 5

**Complete console output:**

```
Geef score van Student A: 77
Geef score van Student B: 34
Geef score van Student C: 65
Geef score van Student D: 85
Geef score van Student E: 25
De hoogste score is 85 van Student D.
De laagste score is 25 van Student E.
Het gemiddelde is 57.2.
```

**Input:**

```
77
34
65
85
25
```

**Expected Output:**

```
De hoogste score is 85 van Student D.
De laagste score is 25 van Student E.
Het gemiddelde is 57.2.
```

---

### Case 6

**Complete console output:**

```
Geef score van Student A: 63
Geef score van Student B: 63
Geef score van Student C: 27
Geef score van Student D: 25
Geef score van Student E: 42
De hoogste score is 63 van Student A.
De laagste score is 25 van Student D.
Het gemiddelde is 44.
```

**Input:**

```
63
63
27
25
42
```

**Expected Output:**

```
De hoogste score is 63 van Student A.
De laagste score is 25 van Student D.
Het gemiddelde is 44.
```

---

### Case 7

**Complete console output:**

```
Geef score van Student A: 4
Geef score van Student B: 58
Geef score van Student C: 36
Geef score van Student D: 1
Geef score van Student E: 29
De hoogste score is 58 van Student B.
De laagste score is 1 van Student D.
Het gemiddelde is 25.6.
```

**Input:**

```
4
58
36
1
29
```

**Expected Output:**

```
De hoogste score is 58 van Student B.
De laagste score is 1 van Student D.
Het gemiddelde is 25.6.
```

---

### Case 8

**Complete console output:**

```
Geef score van Student A: 77
Geef score van Student B: 51
Geef score van Student C: 83
Geef score van Student D: 9
Geef score van Student E: 52
De hoogste score is 83 van Student C.
De laagste score is 9 van Student D.
Het gemiddelde is 54.4.
```

**Input:**

```
77
51
83
9
52
```

**Expected Output:**

```
De hoogste score is 83 van Student C.
De laagste score is 9 van Student D.
Het gemiddelde is 54.4.
```

---

### Case 9

**Complete console output:**

```
Geef score van Student A: 28
Geef score van Student B: 62
Geef score van Student C: 65
Geef score van Student D: 96
Geef score van Student E: 68
De hoogste score is 96 van Student D.
De laagste score is 28 van Student A.
Het gemiddelde is 63.8.
```

**Input:**

```
28
62
65
96
68
```

**Expected Output:**

```
De hoogste score is 96 van Student D.
De laagste score is 28 van Student A.
Het gemiddelde is 63.8.
```

---

### Case 10

**Complete console output:**

```
Geef score van Student A: 92
Geef score van Student B: 31
Geef score van Student C: 42
Geef score van Student D: 62
Geef score van Student E: 42
De hoogste score is 92 van Student A.
De laagste score is 31 van Student B.
Het gemiddelde is 53.8.
```

**Input:**

```
92
31
42
62
42
```

**Expected Output:**

```
De hoogste score is 92 van Student A.
De laagste score is 31 van Student B.
Het gemiddelde is 53.8.
```

---

### Case 11

**Complete console output:**

```
Geef score van Student A: 62
Geef score van Student B: 98
Geef score van Student C: 82
Geef score van Student D: 46
Geef score van Student E: 65
De hoogste score is 98 van Student B.
De laagste score is 46 van Student D.
Het gemiddelde is 70.6.
```

**Input:**

```
62
98
82
46
65
```

**Expected Output:**

```
De hoogste score is 98 van Student B.
De laagste score is 46 van Student D.
Het gemiddelde is 70.6.
```

---

### Case 12

**Complete console output:**

```
Geef score van Student A: 43
Geef score van Student B: 93
Geef score van Student C: 91
Geef score van Student D: 68
Geef score van Student E: 9
De hoogste score is 93 van Student B.
De laagste score is 9 van Student E.
Het gemiddelde is 60.8.
```

**Input:**

```
43
93
91
68
9
```

**Expected Output:**

```
De hoogste score is 93 van Student B.
De laagste score is 9 van Student E.
Het gemiddelde is 60.8.
```

---

### Case 13

**Complete console output:**

```
Geef score van Student A: 4
Geef score van Student B: 49
Geef score van Student C: 88
Geef score van Student D: 64
Geef score van Student E: 25
De hoogste score is 88 van Student C.
De laagste score is 4 van Student A.
Het gemiddelde is 46.
```

**Input:**

```
4
49
88
64
25
```

**Expected Output:**

```
De hoogste score is 88 van Student C.
De laagste score is 4 van Student A.
Het gemiddelde is 46.
```

---

### Case 14

**Complete console output:**

```
Geef score van Student A: 27
Geef score van Student B: 45
Geef score van Student C: 76
Geef score van Student D: 19
Geef score van Student E: 19
De hoogste score is 76 van Student C.
De laagste score is 19 van Student D.
Het gemiddelde is 37.2.
```

**Input:**

```
27
45
76
19
19
```

**Expected Output:**

```
De hoogste score is 76 van Student C.
De laagste score is 19 van Student D.
Het gemiddelde is 37.2.
```

---

### Case 15

**Complete console output:**

```
Geef score van Student A: 85
Geef score van Student B: 75
Geef score van Student C: 8
Geef score van Student D: 42
Geef score van Student E: 94
De hoogste score is 94 van Student E.
De laagste score is 8 van Student C.
Het gemiddelde is 60.8.
```

**Input:**

```
85
75
8
42
94
```

**Expected Output:**

```
De hoogste score is 94 van Student E.
De laagste score is 8 van Student C.
Het gemiddelde is 60.8.
```

---
