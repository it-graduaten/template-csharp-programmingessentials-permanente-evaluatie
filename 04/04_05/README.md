# 04_05

Een school wil een systeem bouwen om studenten te registreren en hun stemmen bij te houden. De school heeft exact twee kandidaat-borgmeesters: Anna en Bart.

Gebruik een List<string> om de namen van de gestemden bij te houden.

Vraag de gebruiker eerst hoeveel studenten er gaan stemmen. Vervolgens vraag je voor elke student:
1. De naam van de student.
2. Voor welke kandidaat ze stemmen (Anna of Bart).

Sla de naam van elke student op in de lijst. Tel ook het aantal stemmen voor Anna en Bart apart bij.

Tonen na alle stemmen: het totaal aantal stemmen, het aantal stemmen voor Anna, het aantal stemmen voor Bart, en wie gewonnen heeft.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Description:** Run 1: args=1, xZYiM, bart, uKymW, anna, GS079, bart


**Input:**

```
1
xZYiM
bart
uKymW
anna
GS079
bart
```

**Expected Output:**

```
Naam van student 1: Totaal aantal stemmen: 1
Stemmen voor Anna: 0
Stemmen voor Bart: 1
Bart heeft gewonnen!
```

---

### Case 2

**Description:** Run 2: args=3, iR7M6, anna, cb7VS, anna, Gqjdf, bart


**Input:**

```
3
iR7M6
anna
cb7VS
anna
Gqjdf
bart
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Naam van student 3: Totaal aantal stemmen: 3
Stemmen voor Anna: 2
Stemmen voor Bart: 1
Anna heeft gewonnen!
```

---

### Case 3

**Description:** Run 3: args=2, Rn6l5, bart, eglti, anna, QYdJa, bart


**Input:**

```
2
Rn6l5
bart
eglti
anna
QYdJa
bart
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Totaal aantal stemmen: 2
Stemmen voor Anna: 1
Stemmen voor Bart: 1
Het is een gelijke stand!
```

---

### Case 4

**Description:** Run 4: args=2, LpxgS, bart, n6xWk, bart, Dr4tQ, anna


**Input:**

```
2
LpxgS
bart
n6xWk
bart
Dr4tQ
anna
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Totaal aantal stemmen: 2
Stemmen voor Anna: 0
Stemmen voor Bart: 2
Bart heeft gewonnen!
```

---

### Case 5

**Description:** Run 5: args=1, Gbpjg, bart, aLUMv, anna, jUxOu, bart


**Input:**

```
1
Gbpjg
bart
aLUMv
anna
jUxOu
bart
```

**Expected Output:**

```
Naam van student 1: Totaal aantal stemmen: 1
Stemmen voor Anna: 0
Stemmen voor Bart: 1
Bart heeft gewonnen!
```

---

### Case 6

**Description:** Run 6: args=1, WlW2l, anna, MB11T, anna, VlUJM, anna


**Input:**

```
1
WlW2l
anna
MB11T
anna
VlUJM
anna
```

**Expected Output:**

```
Naam van student 1: Totaal aantal stemmen: 1
Stemmen voor Anna: 1
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

---

### Case 7

**Description:** Run 7: args=1, 4esEE, anna, C7qgq, bart, MmvBL, bart


**Input:**

```
1
4esEE
anna
C7qgq
bart
MmvBL
bart
```

**Expected Output:**

```
Naam van student 1: Totaal aantal stemmen: 1
Stemmen voor Anna: 1
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

---

### Case 8

**Description:** Run 8: args=1, fHBol, anna, ypcLi, bart, iQ3J3, bart


**Input:**

```
1
fHBol
anna
ypcLi
bart
iQ3J3
bart
```

**Expected Output:**

```
Naam van student 1: Totaal aantal stemmen: 1
Stemmen voor Anna: 1
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

---

### Case 9

**Description:** Run 9: args=2, e9Lym, anna, a7sIp, anna, KBGCC, bart


**Input:**

```
2
e9Lym
anna
a7sIp
anna
KBGCC
bart
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Totaal aantal stemmen: 2
Stemmen voor Anna: 2
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

---

### Case 10

**Description:** Run 10: args=2, YeAnI, bart, tk0H1, anna, 3XoIY, bart


**Input:**

```
2
YeAnI
bart
tk0H1
anna
3XoIY
bart
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Totaal aantal stemmen: 2
Stemmen voor Anna: 1
Stemmen voor Bart: 1
Het is een gelijke stand!
```

---

### Case 11

**Description:** Run 11: args=1, n3SH3, bart, o92qv, bart, siRc1, bart


**Input:**

```
1
n3SH3
bart
o92qv
bart
siRc1
bart
```

**Expected Output:**

```
Naam van student 1: Totaal aantal stemmen: 1
Stemmen voor Anna: 0
Stemmen voor Bart: 1
Bart heeft gewonnen!
```

---

### Case 12

**Description:** Run 12: args=1, lqtZt, anna, 9GEKg, anna, qLGDc, anna


**Input:**

```
1
lqtZt
anna
9GEKg
anna
qLGDc
anna
```

**Expected Output:**

```
Naam van student 1: Totaal aantal stemmen: 1
Stemmen voor Anna: 1
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

---

### Case 13

**Description:** Run 13: args=1, poxuM, anna, fThpI, bart, zMpbv, bart


**Input:**

```
1
poxuM
anna
fThpI
bart
zMpbv
bart
```

**Expected Output:**

```
Naam van student 1: Totaal aantal stemmen: 1
Stemmen voor Anna: 1
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

---

### Case 14

**Description:** Run 14: args=2, sAUtU, bart, o3Nda, bart, BwL2g, anna


**Input:**

```
2
sAUtU
bart
o3Nda
bart
BwL2g
anna
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Totaal aantal stemmen: 2
Stemmen voor Anna: 0
Stemmen voor Bart: 2
Bart heeft gewonnen!
```

---

### Case 15

**Description:** Run 15: args=3, LR05E, anna, FUtmg, anna, Xn2TO, anna


**Input:**

```
3
LR05E
anna
FUtmg
anna
Xn2TO
anna
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Naam van student 3: Totaal aantal stemmen: 3
Stemmen voor Anna: 3
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

---
