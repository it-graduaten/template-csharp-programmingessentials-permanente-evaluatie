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
Hoeveel scores wil je invoeren? 3
Score 1: 8
Score 2: 12
Score 3: 15
Geslaagd: 2
Aantal gezakt: Ja
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
Aantal gezakt: Ja
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
Aantal gezakt: Nee
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
Aantal gezakt: Nee
```

---

### Case 3

**Complete console output:**

```
Hoeveel scores wil je invoeren? 2
Score 1: 5
Score 2: 3
Geslaagd: 0
Aantal gezakt: Ja
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
Aantal gezakt: Ja
```

---

### Case 4

**Complete console output:**

```
Hoeveel scores wil je invoeren? 1
Score 1: 10
Geslaagd: 1
Aantal gezakt: Nee
```

**Input:**

```
1
10
```

**Expected Output:**

```
Geslaagd: 1
Aantal gezakt: Nee
```

---

### Case 5

**Complete console output:**

```
Hoeveel scores wil je invoeren? 3
Score 1: 9
Score 2: 10
Score 3: 11
Geslaagd: 2
Aantal gezakt: Ja
```

**Input:**

```
3
9
10
11
```

**Expected Output:**

```
Geslaagd: 2
Aantal gezakt: Ja
```
