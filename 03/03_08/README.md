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

**Complete console output:**

```
Geef je leeftijd: 24
Geef je geslacht (M of V): M
Toegang toegestaan
```

**Input:**

```
24
M
nee
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 2

**Complete console output:**

```
Geef je leeftijd: 18
Geef je geslacht (M of V): V
Toegang toegestaan
```

**Input:**

```
18
V
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 3

**Complete console output:**

```
Geef je leeftijd: 37
Geef je geslacht (M of V): M
Toegang toegestaan
```

**Input:**

```
37
M
nee
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 4

**Complete console output:**

```
Geef je leeftijd: 11
Geef je geslacht (M of V): V
Ben je vergezeld van een volwassene? (ja/neen): ja
Toegang toegestaan
```

**Input:**

```
11
V
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 5

**Complete console output:**

```
Geef je leeftijd: 4
Geef je geslacht (M of V): M
Toegang geweigerd
```

**Input:**

```
4
M
ja
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 6

**Complete console output:**

```
Geef je leeftijd: 12
Geef je geslacht (M of V): V
Ben je vergezeld van een volwassene? (ja/neen): ja
Toegang toegestaan
```

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

### Case 7

**Complete console output:**

```
Geef je leeftijd: 25
Geef je geslacht (M of V): V
Toegang toegestaan
```

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

### Case 8

**Complete console output:**

```
Geef je leeftijd: 25
Geef je geslacht (M of V): V
Toegang toegestaan
```

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

**Complete console output:**

```
Geef je leeftijd: 40
Geef je geslacht (M of V): V
Toegang toegestaan
```

**Input:**

```
40
V
nee
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 10

**Complete console output:**

```
Geef je leeftijd: 34
Geef je geslacht (M of V): M
Toegang toegestaan
```

**Input:**

```
34
M
nee
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 11

**Complete console output:**

```
Geef je leeftijd: 11
Geef je geslacht (M of V): V
Ben je vergezeld van een volwassene? (ja/neen): nee
Toegang geweigerd
```

**Input:**

```
11
V
nee
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 12

**Complete console output:**

```
Geef je leeftijd: 26
Geef je geslacht (M of V): V
Toegang toegestaan
```

**Input:**

```
26
V
nee
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 13

**Complete console output:**

```
Geef je leeftijd: 6
Geef je geslacht (M of V): M
Toegang geweigerd
```

**Input:**

```
6
M
ja
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 14

**Complete console output:**

```
Geef je leeftijd: 1
Geef je geslacht (M of V): M
Toegang geweigerd
```

**Input:**

```
1
M
ja
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 15

**Complete console output:**

```
Geef je leeftijd: 30
Geef je geslacht (M of V): M
Toegang toegestaan
```

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

### Case 16

**Complete console output:**

```
Geef je leeftijd: 4
Geef je geslacht (M of V): V
Toegang geweigerd
```

**Input:**

```
4
V
ja
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 17

**Complete console output:**

```
Geef je leeftijd: 38
Geef je geslacht (M of V): V
Toegang toegestaan
```

**Input:**

```
38
V
ja
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 18

**Complete console output:**

```
Geef je leeftijd: 31
Geef je geslacht (M of V): V
Toegang toegestaan
```

**Input:**

```
31
V
nee
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 19

**Complete console output:**

```
Geef je leeftijd: 2
Geef je geslacht (M of V): M
Toegang geweigerd
```

**Input:**

```
2
M
nee
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 20

**Complete console output:**

```
Geef je leeftijd: 2
Geef je geslacht (M of V): M
Toegang geweigerd
```

**Input:**

```
2
M
ja
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 21

**Complete console output:**

```
Geef je leeftijd: 27
Geef je geslacht (M of V): V
Toegang toegestaan
```

**Input:**

```
27
V
nee
```

**Expected Output:**

```
Toegang toegestaan
```

---

### Case 22

**Complete console output:**

```
Geef je leeftijd: 36
Geef je geslacht (M of V): V
Toegang toegestaan
```

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

### Case 23

**Complete console output:**

```
Geef je leeftijd: 6
Geef je geslacht (M of V): V
Toegang geweigerd
```

**Input:**

```
6
V
ja
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 24

**Complete console output:**

```
Geef je leeftijd: 4
Geef je geslacht (M of V): V
Toegang geweigerd
```

**Input:**

```
4
V
nee
```

**Expected Output:**

```
Toegang geweigerd
```

---

### Case 25

**Complete console output:**

```
Geef je leeftijd: 7
Geef je geslacht (M of V): V
Toegang geweigerd
```

**Input:**

```
7
V
ja
```

**Expected Output:**

```
Toegang geweigerd
```

---
