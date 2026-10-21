# 08_08

Maak een programma dat de gebruiker om een aantal getallen vraagt en vervolgens deze getallen inleest. Het programma bepaalt het grootste getal, het kleinste getal en het gemiddelde van alle ingevoerde getallen.

Het programma moet de volgende methodes bevatten:

- Een methode die een array met getallen ontvangt en het grootste getal teruggeeft
- Een methode die een array met getallen ontvangt en het kleinste getal teruggeeft
- Een methode die een array met getallen ontvangt en het gemiddelde teruggeeft als double

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 5
Getal 1: 25
Getal 2: 5
Getal 3: 0
Getal 4: 15
Getal 5: 15
Grootste: 25
Kleinste: 0
Gemiddelde: 12
```

**Input:**

```
5
25
5
0
15
15
```

**Expected Output:**

```
Grootste: 25
Kleinste: 0
Gemiddelde: 12
```

---

### Case 2

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 3
Getal 1: 5
Getal 2: 0
Getal 3: 42
Grootste: 42
Kleinste: 0
Gemiddelde: 15
```

**Input:**

```
3
5
0
42
```

**Expected Output:**

```
Grootste: 42
Kleinste: 0
Gemiddelde: 15
```

---

### Case 3

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 5
Getal 1: 42
Getal 2: 0
Getal 3: -5
Getal 4: 5
Getal 5: 10
Grootste: 42
Kleinste: -5
Gemiddelde: 10
```

**Input:**

```
5
42
0
-5
5
10
```

**Expected Output:**

```
Grootste: 42
Kleinste: -5
Gemiddelde: 10
```

---

### Case 4

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 3
Getal 1: 15
Getal 2: 10
Getal 3: 5
Grootste: 15
Kleinste: 5
Gemiddelde: 10
```

**Input:**

```
3
15
10
5
```

**Expected Output:**

```
Grootste: 15
Kleinste: 5
Gemiddelde: 10
```

---

### Case 5

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 3
Getal 1: 42
Getal 2: 5
Getal 3: -5
Grootste: 42
Kleinste: -5
Gemiddelde: 14
```

**Input:**

```
3
42
5
-5
```

**Expected Output:**

```
Grootste: 42
Kleinste: -5
Gemiddelde: 14
```

---

### Case 6

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 1
Getal 1: 15
Grootste: 15
Kleinste: 15
Gemiddelde: 15
```

**Input:**

```
1
15
```

**Expected Output:**

```
Grootste: 15
Kleinste: 15
Gemiddelde: 15
```

---

### Case 7

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 5
Getal 1: 0
Getal 2: 10
Getal 3: 5
Getal 4: 0
Getal 5: 5
Grootste: 10
Kleinste: 0
Gemiddelde: 4
```

**Input:**

```
5
0
10
5
0
5
```

**Expected Output:**

```
Grootste: 10
Kleinste: 0
Gemiddelde: 4
```

---

### Case 8

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 1
Getal 1: 25
Grootste: 25
Kleinste: 25
Gemiddelde: 25
```

**Input:**

```
1
25
```

**Expected Output:**

```
Grootste: 25
Kleinste: 25
Gemiddelde: 25
```

---

### Case 9

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 3
Getal 1: 25
Getal 2: 5
Getal 3: 25
Grootste: 25
Kleinste: 5
Gemiddelde: 18
```

**Input:**

```
3
25
5
25
```

**Expected Output:**

```
Grootste: 25
Kleinste: 5
Gemiddelde: 18
```

---

### Case 10

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 5
Getal 1: 10
Getal 2: 5
Getal 3: 5
Getal 4: 0
Getal 5: 42
Grootste: 42
Kleinste: 0
Gemiddelde: 12
```

**Input:**

```
5
10
5
5
0
42
```

**Expected Output:**

```
Grootste: 42
Kleinste: 0
Gemiddelde: 12
```

---

### Case 11

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 3
Getal 1: 5
Getal 2: 5
Getal 3: 5
Grootste: 5
Kleinste: 5
Gemiddelde: 5
```

**Input:**

```
3
5
5
5
```

**Expected Output:**

```
Grootste: 5
Kleinste: 5
Gemiddelde: 5
```

---

### Case 12

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 1
Getal 1: 10
Grootste: 10
Kleinste: 10
Gemiddelde: 10
```

**Input:**

```
1
10
```

**Expected Output:**

```
Grootste: 10
Kleinste: 10
Gemiddelde: 10
```

---

### Case 13

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 1
Getal 1: -10
Grootste: -10
Kleinste: -10
Gemiddelde: -10
```

**Input:**

```
1
-10
```

**Expected Output:**

```
Grootste: -10
Kleinste: -10
Gemiddelde: -10
```

---

### Case 14

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 3
Getal 1: 25
Getal 2: 0
Getal 3: -100
Grootste: 25
Kleinste: -100
Gemiddelde: -25
```

**Input:**

```
3
25
0
-100
```

**Expected Output:**

```
Grootste: 25
Kleinste: -100
Gemiddelde: -25
```

---

### Case 15

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 1
Getal 1: 42
Grootste: 42
Kleinste: 42
Gemiddelde: 42
```

**Input:**

```
1
42
```

**Expected Output:**

```
Grootste: 42
Kleinste: 42
Gemiddelde: 42
```

---
