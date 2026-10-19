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
Hoeveel scores wil je invoeren? 3
Score 1: 8
Score 2: 12
Score 3: 15
Geslaagd: 2
Gezakt: 1
Gemiddelde: 11
```

**Input:**

```
3
8
12
15
```

**Expected Output:**

```
Geslaagd: 2
Gezakt: 1
Gemiddelde: 11
```

---

### Case 2

**Complete console output:**

```
Hoeveel scores wil je invoeren? 4
Score 1: 10
Score 2: 15
Score 3: 12
Score 4: 18
Geslaagd: 4
Gezakt: 0
Gemiddelde: 13
```

**Input:**

```
4
10
15
12
18
```

**Expected Output:**

```
Geslaagd: 4
Gezakt: 0
Gemiddelde: 13
```

---

### Case 3

**Complete console output:**

```
Hoeveel scores wil je invoeren? 2
Score 1: 5
Score 2: 3
Geslaagd: 0
Gezakt: 2
Gemiddelde: 4
```

**Input:**

```
2
5
3
```

**Expected Output:**

```
Geslaagd: 0
Gezakt: 2
Gemiddelde: 4
```

---

### Case 4

**Complete console output:**

```
Hoeveel scores wil je invoeren? 5
Score 1: 0
Score 2: 10
Score 3: 20
Score 4: 5
Score 5: 15
Geslaagd: 3
Gezakt: 2
Gemiddelde: 10
```

**Input:**

```
5
0
10
20
5
15
```

**Expected Output:**

```
Geslaagd: 3
Gezakt: 2
Gemiddelde: 10
```

---

### Case 5

**Complete console output:**

```
Hoeveel scores wil je invoeren? 1
Score 1: 10
Geslaagd: 1
Gezakt: 0
Gemiddelde: 10
```

**Input:**

```
1
10
```

**Expected Output:**

```
Geslaagd: 1
Gezakt: 0
Gemiddelde: 10
```
