# 08_04

Maak een programma dat de gebruiker om een aantal scores vraagt, waarna de gebruiker die scores kan invoeren. Het programma bepaalt hoeveel scores er boven de 10 liggen en hoeveel er onder of gelijk aan 10 liggen. Een score van 10 of meer betekent geslaagd.

Het programma moet de volgende methodes bevatten:

- Een methode die een array met scores ontvangt en het aantal geslaagden teruggeeft (een score is geslaagd als deze minstens 10 is)
- Een methode die een array met scores ontvangt en het aantal gezakt als bool teruggeeft (true als er ten minste één score onder de 10 is)

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel scores wil je invoeren? 2
Score 1: 5
Score 2: 5
Geslaagd: 0
Aantal gezakt: Ja
```

**Input:**

```
2
5
5
```

**Expected Output:**

```
Geslaagd: 0
Aantal gezakt: Ja
```

---

### Case 2

**Complete console output:**

```
Hoeveel scores wil je invoeren? 1
Score 1: 15
Geslaagd: 1
Aantal gezakt: Nee
```

**Input:**

```
1
15
```

**Expected Output:**

```
Geslaagd: 1
Aantal gezakt: Nee
```

---

### Case 3

**Complete console output:**

```
Hoeveel scores wil je invoeren? 3
Score 1: 15
Score 2: 9
Score 3: 8
Geslaagd: 1
Aantal gezakt: Ja
```

**Input:**

```
3
15
9
8
```

**Expected Output:**

```
Geslaagd: 1
Aantal gezakt: Ja
```

---

### Case 4

**Complete console output:**

```
Hoeveel scores wil je invoeren? 2
Score 1: 10
Score 2: 18
Geslaagd: 2
Aantal gezakt: Nee
```

**Input:**

```
2
10
18
```

**Expected Output:**

```
Geslaagd: 2
Aantal gezakt: Nee
```

---

### Case 5

**Complete console output:**

```
Hoeveel scores wil je invoeren? 4
Score 1: 18
Score 2: 18
Score 3: 12
Score 4: 8
Geslaagd: 3
Aantal gezakt: Ja
```

**Input:**

```
4
18
18
12
8
```

**Expected Output:**

```
Geslaagd: 3
Aantal gezakt: Ja
```

---

### Case 6

**Complete console output:**

```
Hoeveel scores wil je invoeren? 3
Score 1: 5
Score 2: 18
Score 3: 10
Geslaagd: 2
Aantal gezakt: Ja
```

**Input:**

```
3
5
18
10
```

**Expected Output:**

```
Geslaagd: 2
Aantal gezakt: Ja
```

---

### Case 7

**Complete console output:**

```
Hoeveel scores wil je invoeren? 3
Score 1: 3
Score 2: 10
Score 3: 3
Geslaagd: 1
Aantal gezakt: Ja
```

**Input:**

```
3
3
10
3
```

**Expected Output:**

```
Geslaagd: 1
Aantal gezakt: Ja
```

---

### Case 8

**Complete console output:**

```
Hoeveel scores wil je invoeren? 4
Score 1: 8
Score 2: 9
Score 3: 12
Score 4: 18
Geslaagd: 2
Aantal gezakt: Ja
```

**Input:**

```
4
8
9
12
18
```

**Expected Output:**

```
Geslaagd: 2
Aantal gezakt: Ja
```

---

### Case 9

**Complete console output:**

```
Hoeveel scores wil je invoeren? 4
Score 1: 18
Score 2: 18
Score 3: 5
Score 4: 15
Geslaagd: 3
Aantal gezakt: Ja
```

**Input:**

```
4
18
18
5
15
```

**Expected Output:**

```
Geslaagd: 3
Aantal gezakt: Ja
```

---

### Case 10

**Complete console output:**

```
Hoeveel scores wil je invoeren? 3
Score 1: 15
Score 2: 18
Score 3: 3
Geslaagd: 2
Aantal gezakt: Ja
```

**Input:**

```
3
15
18
3
```

**Expected Output:**

```
Geslaagd: 2
Aantal gezakt: Ja
```

---

### Case 11

**Complete console output:**

```
Hoeveel scores wil je invoeren? 2
Score 1: 15
Score 2: 15
Geslaagd: 2
Aantal gezakt: Nee
```

**Input:**

```
2
15
15
```

**Expected Output:**

```
Geslaagd: 2
Aantal gezakt: Nee
```

---

### Case 12

**Complete console output:**

```
Hoeveel scores wil je invoeren? 3
Score 1: 18
Score 2: 3
Score 3: 5
Geslaagd: 1
Aantal gezakt: Ja
```

**Input:**

```
3
18
3
5
```

**Expected Output:**

```
Geslaagd: 1
Aantal gezakt: Ja
```

---

### Case 13

**Complete console output:**

```
Hoeveel scores wil je invoeren? 4
Score 1: 15
Score 2: 18
Score 3: 10
Score 4: 12
Geslaagd: 4
Aantal gezakt: Nee
```

**Input:**

```
4
15
18
10
12
```

**Expected Output:**

```
Geslaagd: 4
Aantal gezakt: Nee
```

---

### Case 14

**Complete console output:**

```
Hoeveel scores wil je invoeren? 2
Score 1: 8
Score 2: 18
Geslaagd: 1
Aantal gezakt: Ja
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
Aantal gezakt: Ja
```

---

### Case 15

**Complete console output:**

```
Hoeveel scores wil je invoeren? 2
Score 1: 9
Score 2: 9
Geslaagd: 0
Aantal gezakt: Ja
```

**Input:**

```
2
9
9
```

**Expected Output:**

```
Geslaagd: 0
Aantal gezakt: Ja
```

---
