# 03_08

Een pretpark hanteert de volgende toegangspolitiek:

- Personen jonger dan 10 jaar mogen het park niet binnen zonder begeleiding van een volwassene.
- Personen tussen 10 en 17 jaar mogen het park alleen binnen als ze vergezeld zijn van een volwassene.
- Personen 18 jaar en ouder mogen altijd het park betreden.

Vraag de gebruiker om zijn leeftijd en geslacht (M of V). Als de persoon tussen 10 en 17 jaar oud is, vraag dan ook of hij/zij vergezeld is van een volwassene (ja/nee). Toon "Toegang toegestaan" of "Toegang geweigerd".

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Description:** Run 1: args=17, M, nee


**Input:**

```
17
M
nee
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 2

**Description:** Run 2: args=29, V, ja


**Input:**

```
29
V
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 3

**Description:** Run 3: args=29, V, nee


**Input:**

```
29
V
nee
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 4

**Description:** Run 4: args=17, M, nee


**Input:**

```
17
M
nee
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 5

**Description:** Run 5: args=32, M, ja


**Input:**

```
32
M
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 6

**Description:** Run 6: args=0, M, nee


**Input:**

```
0
M
nee
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 7

**Description:** Run 7: args=33, V, ja


**Input:**

```
33
V
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 8

**Description:** Run 8: args=25, V, ja


**Input:**

```
25
V
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 9

**Description:** Run 9: args=19, M, ja


**Input:**

```
19
M
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 10

**Description:** Run 10: args=23, M, nee


**Input:**

```
23
M
nee
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 11

**Description:** Run 11: args=36, V, ja


**Input:**

```
36
V
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 12

**Description:** Run 12: args=25, V, ja


**Input:**

```
25
V
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 13

**Description:** Run 13: args=5, V, ja


**Input:**

```
5
V
ja
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 14

**Description:** Run 14: args=0, M, ja


**Input:**

```
0
M
ja
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 15

**Description:** Run 15: args=30, V, ja


**Input:**

```
30
V
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 16

**Description:** Run 16: args=20, M, ja


**Input:**

```
20
M
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 17

**Description:** Run 17: args=8, V, ja


**Input:**

```
8
V
ja
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 18

**Description:** Run 18: args=12, V, ja


**Input:**

```
12
V
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 19

**Description:** Run 19: args=37, M, ja


**Input:**

```
37
M
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 20

**Description:** Run 20: args=6, M, nee


**Input:**

```
6
M
nee
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 21

**Description:** Run 21: args=10, V, nee


**Input:**

```
10
V
nee
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 22

**Description:** Run 22: args=26, M, ja


**Input:**

```
26
M
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 23

**Description:** Run 23: args=14, M, nee


**Input:**

```
14
M
nee
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 24

**Description:** Run 24: args=37, V, nee


**Input:**

```
37
V
nee
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 25

**Description:** Run 25: args=30, M, nee


**Input:**

```
30
M
nee
```

**Expected Output:**

```
Toegang toegestaan
```

---
