# 05_10

Maak een programma dat de gebruiker vraagt hoeveel scores hij of zij wil invoeren. Vervolgens vraagt het programma die scores één voor één en slaat ze op in een array. Daarna bepaalt het programma hoeveel scores minstens 10 zijn (geslaagd) en hoeveel scores minder dan 10 zijn (gezakt), en toont deze aantallen.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel scores wil je invoeren?
5
Geef score 1: Geef score 2: Geef score 3: Geef score 4: Geef score 5: Geslaagd: 2
Gezakt: 3
```

**Input:**

```
5
-10
13
7
8
11
```

**Expected Output:**

```
Geef score 1: Geef score 2: Geef score 3: Geef score 4: Geef score 5: Geslaagd: 2
Gezakt: 3
```

---

### Case 2

**Complete console output:**

```
Hoeveel scores wil je invoeren?
3
Geef score 1: Geef score 2: Geef score 3: Geslaagd: 1
Gezakt: 2
```

**Input:**

```
3
-6
16
1
```

**Expected Output:**

```
Geef score 1: Geef score 2: Geef score 3: Geslaagd: 1
Gezakt: 2
```

---

### Case 3

**Complete console output:**

```
Hoeveel scores wil je invoeren?
1
Geef score 1: Geslaagd: 0
Gezakt: 1
```

**Input:**

```
1
2
```

**Expected Output:**

```
Geef score 1: Geslaagd: 0
Gezakt: 1
```

---

### Case 4

**Complete console output:**

```
Hoeveel scores wil je invoeren?
5
Geef score 1: Geef score 2: Geef score 3: Geef score 4: Geef score 5: Geslaagd: 2
Gezakt: 3
```

**Input:**

```
5
5
-1
19
7
12
```

**Expected Output:**

```
Geef score 1: Geef score 2: Geef score 3: Geef score 4: Geef score 5: Geslaagd: 2
Gezakt: 3
```

---

### Case 5

**Complete console output:**

```
Hoeveel scores wil je invoeren?
3
Geef score 1: Geef score 2: Geef score 3: Geslaagd: 1
Gezakt: 2
```

**Input:**

```
3
12
-7
2
```

**Expected Output:**

```
Geef score 1: Geef score 2: Geef score 3: Geslaagd: 1
Gezakt: 2
```

---

### Case 6

**Complete console output:**

```
Hoeveel scores wil je invoeren?
4
Geef score 1: Geef score 2: Geef score 3: Geef score 4: Geslaagd: 2
Gezakt: 2
```

**Input:**

```
4
-7
11
12
6
```

**Expected Output:**

```
Geef score 1: Geef score 2: Geef score 3: Geef score 4: Geslaagd: 2
Gezakt: 2
```

---

### Case 7

**Complete console output:**

```
Hoeveel scores wil je invoeren?
1
Geef score 1: Geslaagd: 0
Gezakt: 1
```

**Input:**

```
1
0
```

**Expected Output:**

```
Geef score 1: Geslaagd: 0
Gezakt: 1
```

---

### Case 8

**Complete console output:**

```
Hoeveel scores wil je invoeren?
5
Geef score 1: Geef score 2: Geef score 3: Geef score 4: Geef score 5: Geslaagd: 1
Gezakt: 4
```

**Input:**

```
5
13
5
-2
7
-5
```

**Expected Output:**

```
Geef score 1: Geef score 2: Geef score 3: Geef score 4: Geef score 5: Geslaagd: 1
Gezakt: 4
```

---

### Case 9

**Complete console output:**

```
Hoeveel scores wil je invoeren?
4
Geef score 1: Geef score 2: Geef score 3: Geef score 4: Geslaagd: 1
Gezakt: 3
```

**Input:**

```
4
-4
5
7
14
```

**Expected Output:**

```
Geef score 1: Geef score 2: Geef score 3: Geef score 4: Geslaagd: 1
Gezakt: 3
```

---

### Case 10

**Complete console output:**

```
Hoeveel scores wil je invoeren?
1
Geef score 1: Geslaagd: 1
Gezakt: 0
```

**Input:**

```
1
14
```

**Expected Output:**

```
Geef score 1: Geslaagd: 1
Gezakt: 0
```

---
