# 10_06

Maak een programma dat een eenvoudig rekenmachine-quiz maakt. Het programma stelt de gebruiker een willekeurig optelsom met twee getallen tussen 1 en 20. De gebruiker voert het antwoord in. Het programma controleert of het antwoord correct is.

Het programma stelt de gebruiker vijf vragen. Na elke vraag geeft het aan of het antwoord correct was. Na vijf vragen toont het programma het aantal correcte antwoorden en het percentage.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel is 4 + 1?
40
Fout! Het juiste antwoord is 5.
Hoeveel is 1 + 13?
20
Fout! Het juiste antwoord is 14.
Hoeveel is 20 + 16?
20
Fout! Het juiste antwoord is 36.
Hoeveel is 2 + 1?
10
Fout! Het juiste antwoord is 3.
Hoeveel is 3 + 12?
40
Fout! Het juiste antwoord is 15.
Aantal correct: 0
Percentage: 0%
```

**Input:**

```
40
20
20
10
40
```

**Expected Output:**

```
Fout! Het juiste antwoord is 5.
Fout! Het juiste antwoord is 14.
Fout! Het juiste antwoord is 36.
Fout! Het juiste antwoord is 3.
Fout! Het juiste antwoord is 15.
Aantal correct: 0
Percentage: 0%
```

---

### Case 2

**Complete console output:**

```
Hoeveel is 1 + 7?
40
Fout! Het juiste antwoord is 8.
Hoeveel is 13 + 2?
0
Fout! Het juiste antwoord is 15.
Hoeveel is 16 + 2?
20
Fout! Het juiste antwoord is 18.
Hoeveel is 2 + 1?
0
Fout! Het juiste antwoord is 3.
Hoeveel is 19 + 16?
10
Fout! Het juiste antwoord is 35.
Aantal correct: 0
Percentage: 0%
```

**Input:**

```
40
0
20
0
10
```

**Expected Output:**

```
Fout! Het juiste antwoord is 8.
Fout! Het juiste antwoord is 15.
Fout! Het juiste antwoord is 18.
Fout! Het juiste antwoord is 3.
Fout! Het juiste antwoord is 35.
Aantal correct: 0
Percentage: 0%
```

---

### Case 3

**Complete console output:**

```
Hoeveel is 2 + 3?
30
Fout! Het juiste antwoord is 5.
Hoeveel is 2 + 14?
0
Fout! Het juiste antwoord is 16.
Hoeveel is 15 + 2?
20
Fout! Het juiste antwoord is 17.
Hoeveel is 18 + 6?
20
Fout! Het juiste antwoord is 24.
Hoeveel is 11 + 5?
42
Fout! Het juiste antwoord is 16.
Aantal correct: 0
Percentage: 0%
```

**Input:**

```
30
0
20
20
42
```

**Expected Output:**

```
Fout! Het juiste antwoord is 5.
Fout! Het juiste antwoord is 16.
Fout! Het juiste antwoord is 17.
Fout! Het juiste antwoord is 24.
Fout! Het juiste antwoord is 16.
Aantal correct: 0
Percentage: 0%
```

---

### Case 4

**Complete console output:**

```
Hoeveel is 7 + 14?
30
Fout! Het juiste antwoord is 21.
Hoeveel is 14 + 14?
20
Fout! Het juiste antwoord is 28.
Hoeveel is 10 + 10?
40
Fout! Het juiste antwoord is 20.
Hoeveel is 8 + 2?
10
Correct!
Hoeveel is 18 + 16?
42
Fout! Het juiste antwoord is 34.
Aantal correct: 1
Percentage: 20%
```

**Input:**

```
30
20
40
10
42
```

**Expected Output:**

```
Fout! Het juiste antwoord is 21.
Fout! Het juiste antwoord is 28.
Fout! Het juiste antwoord is 20.
Correct!
Fout! Het juiste antwoord is 34.
Aantal correct: 1
Percentage: 20%
```

---

### Case 5

**Complete console output:**

```
Hoeveel is 1 + 6?
10
Fout! Het juiste antwoord is 7.
Hoeveel is 20 + 8?
20
Fout! Het juiste antwoord is 28.
Hoeveel is 19 + 9?
30
Fout! Het juiste antwoord is 28.
Hoeveel is 18 + 20?
0
Fout! Het juiste antwoord is 38.
Hoeveel is 5 + 19?
0
Fout! Het juiste antwoord is 24.
Aantal correct: 0
Percentage: 0%
```

**Input:**

```
10
20
30
0
0
```

**Expected Output:**

```
Fout! Het juiste antwoord is 7.
Fout! Het juiste antwoord is 28.
Fout! Het juiste antwoord is 28.
Fout! Het juiste antwoord is 38.
Fout! Het juiste antwoord is 24.
Aantal correct: 0
Percentage: 0%
```

---

### Case 6

**Complete console output:**

```
Hoeveel is 18 + 15?
42
Fout! Het juiste antwoord is 33.
Hoeveel is 5 + 10?
42
Fout! Het juiste antwoord is 15.
Hoeveel is 17 + 11?
20
Fout! Het juiste antwoord is 28.
Hoeveel is 18 + 13?
42
Fout! Het juiste antwoord is 31.
Hoeveel is 15 + 6?
20
Fout! Het juiste antwoord is 21.
Aantal correct: 0
Percentage: 0%
```

**Input:**

```
42
42
20
42
20
```

**Expected Output:**

```
Fout! Het juiste antwoord is 33.
Fout! Het juiste antwoord is 15.
Fout! Het juiste antwoord is 28.
Fout! Het juiste antwoord is 31.
Fout! Het juiste antwoord is 21.
Aantal correct: 0
Percentage: 0%
```

---

### Case 7

**Complete console output:**

```
Hoeveel is 20 + 2?
30
Fout! Het juiste antwoord is 22.
Hoeveel is 15 + 4?
40
Fout! Het juiste antwoord is 19.
Hoeveel is 10 + 7?
20
Fout! Het juiste antwoord is 17.
Hoeveel is 20 + 2?
10
Fout! Het juiste antwoord is 22.
Hoeveel is 4 + 19?
20
Fout! Het juiste antwoord is 23.
Aantal correct: 0
Percentage: 0%
```

**Input:**

```
30
40
20
10
20
```

**Expected Output:**

```
Fout! Het juiste antwoord is 22.
Fout! Het juiste antwoord is 19.
Fout! Het juiste antwoord is 17.
Fout! Het juiste antwoord is 22.
Fout! Het juiste antwoord is 23.
Aantal correct: 0
Percentage: 0%
```

---

### Case 8

**Complete console output:**

```
Hoeveel is 9 + 5?
40
Fout! Het juiste antwoord is 14.
Hoeveel is 3 + 13?
42
Fout! Het juiste antwoord is 16.
Hoeveel is 11 + 3?
42
Fout! Het juiste antwoord is 14.
Hoeveel is 7 + 12?
30
Fout! Het juiste antwoord is 19.
Hoeveel is 15 + 7?
40
Fout! Het juiste antwoord is 22.
Aantal correct: 0
Percentage: 0%
```

**Input:**

```
40
42
42
30
40
```

**Expected Output:**

```
Fout! Het juiste antwoord is 14.
Fout! Het juiste antwoord is 16.
Fout! Het juiste antwoord is 14.
Fout! Het juiste antwoord is 19.
Fout! Het juiste antwoord is 22.
Aantal correct: 0
Percentage: 0%
```

---

### Case 9

**Complete console output:**

```
Hoeveel is 16 + 5?
0
Fout! Het juiste antwoord is 21.
Hoeveel is 11 + 4?
30
Fout! Het juiste antwoord is 15.
Hoeveel is 13 + 5?
40
Fout! Het juiste antwoord is 18.
Hoeveel is 18 + 20?
10
Fout! Het juiste antwoord is 38.
Hoeveel is 6 + 15?
20
Fout! Het juiste antwoord is 21.
Aantal correct: 0
Percentage: 0%
```

**Input:**

```
0
30
40
10
20
```

**Expected Output:**

```
Fout! Het juiste antwoord is 21.
Fout! Het juiste antwoord is 15.
Fout! Het juiste antwoord is 18.
Fout! Het juiste antwoord is 38.
Fout! Het juiste antwoord is 21.
Aantal correct: 0
Percentage: 0%
```

---

### Case 10

**Complete console output:**

```
Hoeveel is 18 + 10?
30
Fout! Het juiste antwoord is 28.
Hoeveel is 17 + 17?
20
Fout! Het juiste antwoord is 34.
Hoeveel is 16 + 18?
20
Fout! Het juiste antwoord is 34.
Hoeveel is 20 + 20?
10
Fout! Het juiste antwoord is 40.
Hoeveel is 18 + 11?
0
Fout! Het juiste antwoord is 29.
Aantal correct: 0
Percentage: 0%
```

**Input:**

```
30
20
20
10
0
```

**Expected Output:**

```
Fout! Het juiste antwoord is 28.
Fout! Het juiste antwoord is 34.
Fout! Het juiste antwoord is 34.
Fout! Het juiste antwoord is 40.
Fout! Het juiste antwoord is 29.
Aantal correct: 0
Percentage: 0%
```

---

### Case 11

**Complete console output:**

```
Hoeveel is 14 + 1?
0
Fout! Het juiste antwoord is 15.
Hoeveel is 1 + 9?
40
Fout! Het juiste antwoord is 10.
Hoeveel is 10 + 2?
20
Fout! Het juiste antwoord is 12.
Hoeveel is 15 + 20?
20
Fout! Het juiste antwoord is 35.
Hoeveel is 12 + 9?
0
Fout! Het juiste antwoord is 21.
Aantal correct: 0
Percentage: 0%
```

**Input:**

```
0
40
20
20
0
```

**Expected Output:**

```
Fout! Het juiste antwoord is 15.
Fout! Het juiste antwoord is 10.
Fout! Het juiste antwoord is 12.
Fout! Het juiste antwoord is 35.
Fout! Het juiste antwoord is 21.
Aantal correct: 0
Percentage: 0%
```

---

### Case 12

**Complete console output:**

```
Hoeveel is 12 + 10?
40
Fout! Het juiste antwoord is 22.
Hoeveel is 9 + 7?
10
Fout! Het juiste antwoord is 16.
Hoeveel is 1 + 17?
30
Fout! Het juiste antwoord is 18.
Hoeveel is 10 + 10?
42
Fout! Het juiste antwoord is 20.
Hoeveel is 19 + 7?
20
Fout! Het juiste antwoord is 26.
Aantal correct: 0
Percentage: 0%
```

**Input:**

```
40
10
30
42
20
```

**Expected Output:**

```
Fout! Het juiste antwoord is 22.
Fout! Het juiste antwoord is 16.
Fout! Het juiste antwoord is 18.
Fout! Het juiste antwoord is 20.
Fout! Het juiste antwoord is 26.
Aantal correct: 0
Percentage: 0%
```

---

### Case 13

**Complete console output:**

```
Hoeveel is 11 + 2?
30
Fout! Het juiste antwoord is 13.
Hoeveel is 12 + 13?
0
Fout! Het juiste antwoord is 25.
Hoeveel is 13 + 18?
10
Fout! Het juiste antwoord is 31.
Hoeveel is 8 + 18?
10
Fout! Het juiste antwoord is 26.
Hoeveel is 18 + 5?
30
Fout! Het juiste antwoord is 23.
Aantal correct: 0
Percentage: 0%
```

**Input:**

```
30
0
10
10
30
```

**Expected Output:**

```
Fout! Het juiste antwoord is 13.
Fout! Het juiste antwoord is 25.
Fout! Het juiste antwoord is 31.
Fout! Het juiste antwoord is 26.
Fout! Het juiste antwoord is 23.
Aantal correct: 0
Percentage: 0%
```

---

### Case 14

**Complete console output:**

```
Hoeveel is 14 + 16?
30
Correct!
Hoeveel is 7 + 12?
20
Fout! Het juiste antwoord is 19.
Hoeveel is 18 + 5?
0
Fout! Het juiste antwoord is 23.
Hoeveel is 17 + 8?
0
Fout! Het juiste antwoord is 25.
Hoeveel is 3 + 11?
0
Fout! Het juiste antwoord is 14.
Aantal correct: 1
Percentage: 20%
```

**Input:**

```
30
20
0
0
0
```

**Expected Output:**

```
Correct!
Fout! Het juiste antwoord is 19.
Fout! Het juiste antwoord is 23.
Fout! Het juiste antwoord is 25.
Fout! Het juiste antwoord is 14.
Aantal correct: 1
Percentage: 20%
```

---

### Case 15

**Complete console output:**

```
Hoeveel is 6 + 19?
30
Fout! Het juiste antwoord is 25.
Hoeveel is 15 + 6?
20
Fout! Het juiste antwoord is 21.
Hoeveel is 3 + 15?
40
Fout! Het juiste antwoord is 18.
Hoeveel is 1 + 19?
20
Correct!
Hoeveel is 6 + 12?
40
Fout! Het juiste antwoord is 18.
Aantal correct: 1
Percentage: 20%
```

**Input:**

```
30
20
40
20
40
```

**Expected Output:**

```
Fout! Het juiste antwoord is 25.
Fout! Het juiste antwoord is 21.
Fout! Het juiste antwoord is 18.
Correct!
Fout! Het juiste antwoord is 18.
Aantal correct: 1
Percentage: 20%
```

---
