# 05_05

Maak een programma dat de gebruiker vraagt hoeveel getallen hij of zij wil invoeren. Vervolgens vraagt het programma die getallen één voor één en slaat ze op in een array. Daarna vraagt het programma naar een getal om te zoeken. Het programma doorzoekt de array naar dat getal en toont of het gevonden is, en zo ja, op welke index(en) het zich bevindt.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel getallen wil je invoeren?
1
Geef getal 1: Geef een getal om te zoeken: 3
Het getal 0 is niet gevonden.
```

**Input:**

```
1
3
0
```

**Expected Output:**

```
Geef getal 1: Het getal 0 is niet gevonden.
```

---

### Case 2

**Complete console output:**

```
Hoeveel getallen wil je invoeren?
3
Geef getal 1: Geef getal 2: Geef getal 3: Geef een getal om te zoeken: 20
Het getal -8 is niet gevonden.
```

**Input:**

```
3
20
-10
8
-8
```

**Expected Output:**

```
Geef getal 1: Geef getal 2: Geef getal 3: Het getal -8 is niet gevonden.
```

---

### Case 3

**Complete console output:**

```
Hoeveel getallen wil je invoeren?
4
Geef getal 1: Geef getal 2: Geef getal 3: Geef getal 4: Geef een getal om te zoeken: 2
Het getal 17 is niet gevonden.
```

**Input:**

```
4
2
19
-9
-1
17
```

**Expected Output:**

```
Geef getal 1: Geef getal 2: Geef getal 3: Geef getal 4: Het getal 17 is niet gevonden.
```

---

### Case 4

**Complete console output:**

```
Hoeveel getallen wil je invoeren?
1
Geef getal 1: Geef een getal om te zoeken: 20
Het getal 10 is niet gevonden.
```

**Input:**

```
1
20
10
```

**Expected Output:**

```
Geef getal 1: Het getal 10 is niet gevonden.
```

---

### Case 5

**Complete console output:**

```
Hoeveel getallen wil je invoeren?
4
Geef getal 1: Geef getal 2: Geef getal 3: Geef getal 4: Geef een getal om te zoeken: 0
Het getal -1 is niet gevonden.
```

**Input:**

```
4
0
13
-9
18
-1
```

**Expected Output:**

```
Geef getal 1: Geef getal 2: Geef getal 3: Geef getal 4: Het getal -1 is niet gevonden.
```

---

### Case 6

**Complete console output:**

```
Hoeveel getallen wil je invoeren?
4
Geef getal 1: Geef getal 2: Geef getal 3: Geef getal 4: Geef een getal om te zoeken: 9
Het getal -3 is niet gevonden.
```

**Input:**

```
4
9
-10
15
13
-3
```

**Expected Output:**

```
Geef getal 1: Geef getal 2: Geef getal 3: Geef getal 4: Het getal -3 is niet gevonden.
```

---

### Case 7

**Complete console output:**

```
Hoeveel getallen wil je invoeren?
3
Geef getal 1: Geef getal 2: Geef getal 3: Geef een getal om te zoeken: -4
Het getal -4 is gevonden op de volgende index(en):
0
```

**Input:**

```
3
-4
1
-9
-4
```

**Expected Output:**

```
Geef getal 1: Geef getal 2: Geef getal 3: Het getal -4 is gevonden op de volgende index(en):
0
```

---

### Case 8

**Complete console output:**

```
Hoeveel getallen wil je invoeren?
1
Geef getal 1: Geef een getal om te zoeken: 14
Het getal -1 is niet gevonden.
```

**Input:**

```
1
14
-1
```

**Expected Output:**

```
Geef getal 1: Het getal -1 is niet gevonden.
```

---

### Case 9

**Complete console output:**

```
Hoeveel getallen wil je invoeren?
2
Geef getal 1: Geef getal 2: Geef een getal om te zoeken: -2
Het getal -3 is niet gevonden.
```

**Input:**

```
2
-2
-1
-3
```

**Expected Output:**

```
Geef getal 1: Geef getal 2: Het getal -3 is niet gevonden.
```

---

### Case 10

**Complete console output:**

```
Hoeveel getallen wil je invoeren?
3
Geef getal 1: Geef getal 2: Geef getal 3: Geef een getal om te zoeken: 19
Het getal 4 is gevonden op de volgende index(en):
1
```

**Input:**

```
3
19
4
-8
4
```

**Expected Output:**

```
Geef getal 1: Geef getal 2: Geef getal 3: Het getal 4 is gevonden op de volgende index(en):
1
```

---
