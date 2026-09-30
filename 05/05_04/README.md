# 05_04

Maak een programma dat de gebruiker vraagt hoeveel namen hij of zij wil invoeren. Vervolgens vraagt het programma die namen één voor één en slaat ze op in een array. Daarna vraagt het programma naar een letter, en telt het hoeveel namen beginnen met die letter (ongeacht hoofd- of kleine letters). Het programma toont het aantal namen dat met die letter begint.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel namen wil je invoeren?
2
Geef naam 1: Geef naam 2: Geef een letter: Kristien
Aantal namen dat begint met 'V': 0
```

**Input:**

```
2
Kristien
Julien
V
```

**Expected Output:**

```
Geef naam 1: Geef naam 2: Aantal namen dat begint met 'V': 0
```

---

### Case 2

**Complete console output:**

```
Hoeveel namen wil je invoeren?
1
Geef naam 1: Geef een letter: Mauro
Aantal namen dat begint met 'W': 0
```

**Input:**

```
1
Mauro
W
```

**Expected Output:**

```
Geef naam 1: Aantal namen dat begint met 'W': 0
```

---

### Case 3

**Complete console output:**

```
Hoeveel namen wil je invoeren?
1
Geef naam 1: Geef een letter: Pieter
Aantal namen dat begint met 'W': 0
```

**Input:**

```
1
Pieter
W
```

**Expected Output:**

```
Geef naam 1: Aantal namen dat begint met 'W': 0
```

---

### Case 4

**Complete console output:**

```
Hoeveel namen wil je invoeren?
4
Geef naam 1: Geef naam 2: Geef naam 3: Geef naam 4: Geef een letter: Tom
Aantal namen dat begint met 'T': 1
```

**Input:**

```
4
Tom
Johan
Nancy
Eline
T
```

**Expected Output:**

```
Geef naam 1: Geef naam 2: Geef naam 3: Geef naam 4: Aantal namen dat begint met 'T': 1
```

---

### Case 5

**Complete console output:**

```
Hoeveel namen wil je invoeren?
5
Geef naam 1: Geef naam 2: Geef naam 3: Geef naam 4: Geef naam 5: Geef een letter: Mario
Aantal namen dat begint met 'J': 2
```

**Input:**

```
5
Mario
Joanna
Ine
Jenny
Yvonne
J
```

**Expected Output:**

```
Geef naam 1: Geef naam 2: Geef naam 3: Geef naam 4: Geef naam 5: Aantal namen dat begint met 'J': 2
```

---

### Case 6

**Complete console output:**

```
Hoeveel namen wil je invoeren?
1
Geef naam 1: Geef een letter: Monique
Aantal namen dat begint met 'L': 0
```

**Input:**

```
1
Monique
L
```

**Expected Output:**

```
Geef naam 1: Aantal namen dat begint met 'L': 0
```

---

### Case 7

**Complete console output:**

```
Hoeveel namen wil je invoeren?
3
Geef naam 1: Geef naam 2: Geef naam 3: Geef een letter: Kim
Aantal namen dat begint met 'E': 0
```

**Input:**

```
3
Kim
Ruben
Petra
E
```

**Expected Output:**

```
Geef naam 1: Geef naam 2: Geef naam 3: Aantal namen dat begint met 'E': 0
```

---

### Case 8

**Complete console output:**

```
Hoeveel namen wil je invoeren?
4
Geef naam 1: Geef naam 2: Geef naam 3: Geef naam 4: Geef een letter: Victoria
Aantal namen dat begint met 'Z': 0
```

**Input:**

```
4
Victoria
Adriana
Wout
Luc
Z
```

**Expected Output:**

```
Geef naam 1: Geef naam 2: Geef naam 3: Geef naam 4: Aantal namen dat begint met 'Z': 0
```

---

### Case 9

**Complete console output:**

```
Hoeveel namen wil je invoeren?
3
Geef naam 1: Geef naam 2: Geef naam 3: Geef een letter: Ward
Aantal namen dat begint met 'J': 0
```

**Input:**

```
3
Ward
Mehdi
Heidi
J
```

**Expected Output:**

```
Geef naam 1: Geef naam 2: Geef naam 3: Aantal namen dat begint met 'J': 0
```

---

### Case 10

**Complete console output:**

```
Hoeveel namen wil je invoeren?
1
Geef naam 1: Geef een letter: Mathias
Aantal namen dat begint met 'A': 0
```

**Input:**

```
1
Mathias
A
```

**Expected Output:**

```
Geef naam 1: Aantal namen dat begint met 'A': 0
```

---
