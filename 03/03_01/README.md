# 03_01

Schrijf een programma dat de gebruiker vraagt om een dag van de week in te geven als getal (1 t/m 7). Het programma toont daarna de naam van de dag in het Nederlands:

- 1 = maandag
- 2 = dinsdag
- 3 = woensdag
- 4 = donderdag
- 5 = vrijdag
- 6 = zaterdag
- 7 = zondag

Als de gebruiker een ongeldig getal invoert (minder dan 1 of meer dan 7), toon dan "Ongeldige dag".

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Description:** Run 1: args=1


**Input:**

```
1
```

**Expected Output:**

```
maandag
```

---

### Case 2

**Description:** Run 2: args=4


**Input:**

```
4
```

**Expected Output:**

```
donderdag
```

---

### Case 3

**Description:** Run 3: args=5


**Input:**

```
5
```

**Expected Output:**

```
vrijdag
```

---

### Case 4

**Description:** Run 4: args=7


**Input:**

```
7
```

**Expected Output:**

```
zondag
```

---

### Case 5

**Description:** Run 5: args=9


**Input:**

```
9
```

**Expected Output:**

```
Ongeldige dag
```

---

### Case 6

**Description:** Run 6: args=10


**Input:**

```
10
```

**Expected Output:**

```
Ongeldige dag
```

---

### Case 7

**Description:** Run 7: args=4


**Input:**

```
4
```

**Expected Output:**

```
donderdag
```

---

### Case 8

**Description:** Run 8: args=6


**Input:**

```
6
```

**Expected Output:**

```
zaterdag
```

---

### Case 9

**Description:** Run 9: args=6


**Input:**

```
6
```

**Expected Output:**

```
zaterdag
```

---

### Case 10

**Description:** Run 10: args=2


**Input:**

```
2
```

**Expected Output:**

```
dinsdag
```

---

### Case 11

**Description:** Run 11: args=0


**Input:**

```
0
```

**Expected Output:**

```
Ongeldige dag
```

---

### Case 12

**Description:** Run 12: args=1


**Input:**

```
1
```

**Expected Output:**

```
maandag
```

---

### Case 13

**Description:** Run 13: args=2


**Input:**

```
2
```

**Expected Output:**

```
dinsdag
```

---

### Case 14

**Description:** Run 14: args=0


**Input:**

```
0
```

**Expected Output:**

```
Ongeldige dag
```

---

### Case 15

**Description:** Run 15: args=4


**Input:**

```
4
```

**Expected Output:**

```
donderdag
```

---

### Case 16

**Description:** Run 16: args=2


**Input:**

```
2
```

**Expected Output:**

```
dinsdag
```

---

### Case 17

**Description:** Run 17: args=10


**Input:**

```
10
```

**Expected Output:**

```
Ongeldige dag
```

---

### Case 18

**Description:** Run 18: args=5


**Input:**

```
5
```

**Expected Output:**

```
vrijdag
```

---

### Case 19

**Description:** Run 19: args=6


**Input:**

```
6
```

**Expected Output:**

```
zaterdag
```

---

### Case 20

**Description:** Run 20: args=7


**Input:**

```
7
```

**Expected Output:**

```
zondag
```

---

### Case 21

**Description:** Run 21: args=10


**Input:**

```
10
```

**Expected Output:**

```
Ongeldige dag
```

---

### Case 22

**Description:** Run 22: args=4


**Input:**

```
4
```

**Expected Output:**

```
donderdag
```

---

### Case 23

**Description:** Run 23: args=5


**Input:**

```
5
```

**Expected Output:**

```
vrijdag
```

---

### Case 24

**Description:** Run 24: args=6


**Input:**

```
6
```

**Expected Output:**

```
zaterdag
```

---

### Case 25

**Description:** Run 25: args=10


**Input:**

```
10
```

**Expected Output:**

```
Ongeldige dag
```

---
