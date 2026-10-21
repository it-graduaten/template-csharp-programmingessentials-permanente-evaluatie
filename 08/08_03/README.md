# 08_03

Maak een programma dat de gebruiker om een aantal dagen vraagt en vervolgens voor elke dag de temperatuur in graden Celsius invoert. Het programma berekent en toont het gemiddelde, de hoogste en de laagste temperatuur.

Het programma moet de volgende methodes bevatten:

- Een methode die de hoogste temperatuur teruggeeft van een array met temperaturen ( ontvangt de array als parameter)
- Een methode die de laagste temperatuur teruggeeft van een array met temperaturen (ontvangst de array als parameter)
- Een methode die het gemiddelde van een array met temperaturen teruggeeft als double (ontvangst de array als parameter)

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 1
Temperatuur dag 1: 10
Gemiddelde: 10
Hoogste: 10
Laagste: 10
```

**Input:**

```
1
10
```

**Expected Output:**

```
Gemiddelde: 10
Hoogste: 10
Laagste: 10
```

---

### Case 2

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 3
Temperatuur dag 1: 20
Temperatuur dag 2: 15
Temperatuur dag 3: 15
Gemiddelde: 16
Hoogste: 20
Laagste: 15
```

**Input:**

```
3
20
15
15
```

**Expected Output:**

```
Gemiddelde: 16
Hoogste: 20
Laagste: 15
```

---

### Case 3

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 5
Temperatuur dag 1: 0
Temperatuur dag 2: -10
Temperatuur dag 3: 10
Temperatuur dag 4: 10
Temperatuur dag 5: 20
Gemiddelde: 6
Hoogste: 20
Laagste: -10
```

**Input:**

```
5
0
-10
10
10
20
```

**Expected Output:**

```
Gemiddelde: 6
Hoogste: 20
Laagste: -10
```

---

### Case 4

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 5
Temperatuur dag 1: 25
Temperatuur dag 2: 10
Temperatuur dag 3: 0
Temperatuur dag 4: 25
Temperatuur dag 5: -10
Gemiddelde: 10
Hoogste: 25
Laagste: -10
```

**Input:**

```
5
25
10
0
25
-10
```

**Expected Output:**

```
Gemiddelde: 10
Hoogste: 25
Laagste: -10
```

---

### Case 5

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 5
Temperatuur dag 1: 0
Temperatuur dag 2: 0
Temperatuur dag 3: 20
Temperatuur dag 4: 25
Temperatuur dag 5: 10
Gemiddelde: 11
Hoogste: 25
Laagste: 0
```

**Input:**

```
5
0
0
20
25
10
```

**Expected Output:**

```
Gemiddelde: 11
Hoogste: 25
Laagste: 0
```

---

### Case 6

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 1
Temperatuur dag 1: 25
Gemiddelde: 25
Hoogste: 25
Laagste: 25
```

**Input:**

```
1
25
```

**Expected Output:**

```
Gemiddelde: 25
Hoogste: 25
Laagste: 25
```

---

### Case 7

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 3
Temperatuur dag 1: 0
Temperatuur dag 2: 25
Temperatuur dag 3: 20
Gemiddelde: 15
Hoogste: 25
Laagste: 0
```

**Input:**

```
3
0
25
20
```

**Expected Output:**

```
Gemiddelde: 15
Hoogste: 25
Laagste: 0
```

---

### Case 8

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 1
Temperatuur dag 1: -10
Gemiddelde: -10
Hoogste: -10
Laagste: -10
```

**Input:**

```
1
-10
```

**Expected Output:**

```
Gemiddelde: -10
Hoogste: -10
Laagste: -10
```

---

### Case 9

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 3
Temperatuur dag 1: 20
Temperatuur dag 2: -10
Temperatuur dag 3: 25
Gemiddelde: 11
Hoogste: 25
Laagste: -10
```

**Input:**

```
3
20
-10
25
```

**Expected Output:**

```
Gemiddelde: 11
Hoogste: 25
Laagste: -10
```

---

### Case 10

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 5
Temperatuur dag 1: 25
Temperatuur dag 2: 20
Temperatuur dag 3: 20
Temperatuur dag 4: 15
Temperatuur dag 5: 15
Gemiddelde: 19
Hoogste: 25
Laagste: 15
```

**Input:**

```
5
25
20
20
15
15
```

**Expected Output:**

```
Gemiddelde: 19
Hoogste: 25
Laagste: 15
```

---

### Case 11

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 3
Temperatuur dag 1: -10
Temperatuur dag 2: -10
Temperatuur dag 3: 20
Gemiddelde: 0
Hoogste: 20
Laagste: -10
```

**Input:**

```
3
-10
-10
20
```

**Expected Output:**

```
Gemiddelde: 0
Hoogste: 20
Laagste: -10
```

---

### Case 12

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 3
Temperatuur dag 1: 0
Temperatuur dag 2: 0
Temperatuur dag 3: 20
Gemiddelde: 6
Hoogste: 20
Laagste: 0
```

**Input:**

```
3
0
0
20
```

**Expected Output:**

```
Gemiddelde: 6
Hoogste: 20
Laagste: 0
```

---

### Case 13

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 3
Temperatuur dag 1: 10
Temperatuur dag 2: 10
Temperatuur dag 3: 20
Gemiddelde: 13
Hoogste: 20
Laagste: 10
```

**Input:**

```
3
10
10
20
```

**Expected Output:**

```
Gemiddelde: 13
Hoogste: 20
Laagste: 10
```

---

### Case 14

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 5
Temperatuur dag 1: 25
Temperatuur dag 2: 15
Temperatuur dag 3: -10
Temperatuur dag 4: 10
Temperatuur dag 5: 10
Gemiddelde: 10
Hoogste: 25
Laagste: -10
```

**Input:**

```
5
25
15
-10
10
10
```

**Expected Output:**

```
Gemiddelde: 10
Hoogste: 25
Laagste: -10
```

---

### Case 15

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 1
Temperatuur dag 1: -10
Gemiddelde: -10
Hoogste: -10
Laagste: -10
```

**Input:**

```
1
-10
```

**Expected Output:**

```
Gemiddelde: -10
Hoogste: -10
Laagste: -10
```

---
