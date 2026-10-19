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
Getal 1: 10
Getal 2: 20
Getal 3: 5
Getal 4: 15
Getal 5: 25
Grootste: 25
Kleinste: 5
Gemiddelde: 15
```

**Input:**

```
5
10
20
5
15
25
```

**Expected Output:**

```
Grootste: 25
Kleinste: 5
Gemiddelde: 15
```

---

### Case 2

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 3
Getal 1: -10
Getal 2: -5
Getal 3: 0
Grootste: 0
Kleinste: -10
Gemiddelde: -5
```

**Input:**

```
3
-10
-5
0
```

**Expected Output:**

```
Grootste: 0
Kleinste: -10
Gemiddelde: -5
```

---

### Case 3

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

### Case 4

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 4
Getal 1: 7
Getal 2: 7
Getal 3: 7
Getal 4: 7
Grootste: 7
Kleinste: 7
Gemiddelde: 7
```

**Input:**

```
4
7
7
7
7
```

**Expected Output:**

```
Grootste: 7
Kleinste: 7
Gemiddelde: 7
```

---

### Case 5

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 3
Getal 1: -100
Getal 2: 100
Getal 3: 0
Grootste: 100
Kleinste: -100
Gemiddelde: 0
```

**Input:**

```
3
-100
100
0
```

**Expected Output:**

```
Grootste: 100
Kleinste: -100
Gemiddelde: 0
```
