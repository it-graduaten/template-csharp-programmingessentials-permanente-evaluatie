# 08_09

Maak een programma dat de gebruiker om een aantal scores vraagt, waarna de gebruiker die scores kan invoeren. Het programma bepaalt het aantal geslaagde studenten (score >= 10), het aantal gezakte studenten (score < 10) en het gemiddelde van alle scores.

Het programma moet de volgende methodes bevatten:

- Een methode die een array met scores ontvangt en het aantal geslaagden teruggeeft (een score is geslaagd als deze minstens 10 is)
- Een methode die een array met scores ontvangt en het aantal gezakt teruggeeft (een score is gezakt als deze minder dan 10 is)
- Een methode die een array met scores ontvangt en het gemiddelde teruggeeft als double
- Een void methode die de resultaten afdrukt (ontvangt het aantal geslaagden, het aantal gezakt en het gemiddelde als parameters)

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel scores wil je invoeren? 1
Score 1: 20
Geslaagd: 1
Gezakt: 0
Gemiddelde: 20
```

**Input:**

```
1
20
```

**Expected Output:**

```
Geslaagd: 1
Gezakt: 0
Gemiddelde: 20
```

---

### Case 2

**Complete console output:**

```
Hoeveel scores wil je invoeren? 3
Score 1: 10
Score 2: 12
Score 3: 20
Geslaagd: 3
Gezakt: 0
Gemiddelde: 14
```

**Input:**

```
3
10
12
20
```

**Expected Output:**

```
Geslaagd: 3
Gezakt: 0
Gemiddelde: 14
```

---

### Case 3

**Complete console output:**

```
Hoeveel scores wil je invoeren? 2
Score 1: 10
Score 2: 10
Geslaagd: 2
Gezakt: 0
Gemiddelde: 10
```

**Input:**

```
2
10
10
```

**Expected Output:**

```
Geslaagd: 2
Gezakt: 0
Gemiddelde: 10
```

---

### Case 4

**Complete console output:**

```
Hoeveel scores wil je invoeren? 3
Score 1: 5
Score 2: 3
Score 3: 8
Geslaagd: 0
Gezakt: 3
Gemiddelde: 5
```

**Input:**

```
3
5
3
8
```

**Expected Output:**

```
Geslaagd: 0
Gezakt: 3
Gemiddelde: 5
```

---

### Case 5

**Complete console output:**

```
Hoeveel scores wil je invoeren? 2
Score 1: 15
Score 2: 8
Geslaagd: 1
Gezakt: 1
Gemiddelde: 11
```

**Input:**

```
2
15
8
```

**Expected Output:**

```
Geslaagd: 1
Gezakt: 1
Gemiddelde: 11
```

---

### Case 6

**Complete console output:**

```
Hoeveel scores wil je invoeren? 4
Score 1: 0
Score 2: 12
Score 3: 10
Score 4: 9
Geslaagd: 2
Gezakt: 2
Gemiddelde: 7
```

**Input:**

```
4
0
12
10
9
```

**Expected Output:**

```
Geslaagd: 2
Gezakt: 2
Gemiddelde: 7
```

---

### Case 7

**Complete console output:**

```
Hoeveel scores wil je invoeren? 1
Score 1: 5
Geslaagd: 0
Gezakt: 1
Gemiddelde: 5
```

**Input:**

```
1
5
```

**Expected Output:**

```
Geslaagd: 0
Gezakt: 1
Gemiddelde: 5
```

---

### Case 8

**Complete console output:**

```
Hoeveel scores wil je invoeren? 4
Score 1: 9
Score 2: 10
Score 3: 9
Score 4: 10
Geslaagd: 2
Gezakt: 2
Gemiddelde: 9
```

**Input:**

```
4
9
10
9
10
```

**Expected Output:**

```
Geslaagd: 2
Gezakt: 2
Gemiddelde: 9
```

---

### Case 9

**Complete console output:**

```
Hoeveel scores wil je invoeren? 3
Score 1: 10
Score 2: 20
Score 3: 0
Geslaagd: 2
Gezakt: 1
Gemiddelde: 10
```

**Input:**

```
3
10
20
0
```

**Expected Output:**

```
Geslaagd: 2
Gezakt: 1
Gemiddelde: 10
```

---

### Case 10

**Complete console output:**

```
Hoeveel scores wil je invoeren? 1
Score 1: 9
Geslaagd: 0
Gezakt: 1
Gemiddelde: 9
```

**Input:**

```
1
9
```

**Expected Output:**

```
Geslaagd: 0
Gezakt: 1
Gemiddelde: 9
```

---

### Case 11

**Complete console output:**

```
Hoeveel scores wil je invoeren? 2
Score 1: 8
Score 2: 18
Geslaagd: 1
Gezakt: 1
Gemiddelde: 13
```

**Input:**

```
2
8
18
```

**Expected Output:**

```
Geslaagd: 1
Gezakt: 1
Gemiddelde: 13
```

---

### Case 12

**Complete console output:**

```
Hoeveel scores wil je invoeren? 3
Score 1: 5
Score 2: 3
Score 3: 18
Geslaagd: 1
Gezakt: 2
Gemiddelde: 8
```

**Input:**

```
3
5
3
18
```

**Expected Output:**

```
Geslaagd: 1
Gezakt: 2
Gemiddelde: 8
```

---

### Case 13

**Complete console output:**

```
Hoeveel scores wil je invoeren? 2
Score 1: 20
Score 2: 5
Geslaagd: 1
Gezakt: 1
Gemiddelde: 12
```

**Input:**

```
2
20
5
```

**Expected Output:**

```
Geslaagd: 1
Gezakt: 1
Gemiddelde: 12
```

---

### Case 14

**Complete console output:**

```
Hoeveel scores wil je invoeren? 3
Score 1: 15
Score 2: 5
Score 3: 0
Geslaagd: 1
Gezakt: 2
Gemiddelde: 6
```

**Input:**

```
3
15
5
0
```

**Expected Output:**

```
Geslaagd: 1
Gezakt: 2
Gemiddelde: 6
```

---

### Case 15

**Complete console output:**

```
Hoeveel scores wil je invoeren? 5
Score 1: 8
Score 2: 3
Score 3: 5
Score 4: 18
Score 5: 15
Geslaagd: 2
Gezakt: 3
Gemiddelde: 9
```

**Input:**

```
5
8
3
5
18
15
```

**Expected Output:**

```
Geslaagd: 2
Gezakt: 3
Gemiddelde: 9
```

---
