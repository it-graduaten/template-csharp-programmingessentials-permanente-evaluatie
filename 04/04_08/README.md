# 04_08

Een gebruiker wil weten welke dag van de week het is op basis van een getal (1 = maandag, ..., 7 = zondag). Gebruik een switch-statement om de naam van de dag te tonen.

Vraag de gebruiker om een getal tussen 1 en 7. Toon de naam van de dag in het Nederlands. Als de gebruiker een ongeldig getal invoert, toon dan "Ongeldige dag".

Daarnaast wil de gebruiker ook weten of deze dag een werkdag is (maandag t/m vrijdag) of een weekenddag (zaterdag of zondag). Toon ook dit.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Description:** Run 1: args=8


**Input:**

```
8
```

**Expected Output:**

```
Ongeldige dag
```

---

### Case 2

**Description:** Run 2: args=3


**Input:**

```
3
```

**Expected Output:**

```
woensdag
werkdag
```

---

### Case 3

**Description:** Run 3: args=6


**Input:**

```
6
```

**Expected Output:**

```
zaterdag
weekenddag
```

---

### Case 4

**Description:** Run 4: args=0


**Input:**

```
0
```

**Expected Output:**

```
Ongeldige dag
```

---

### Case 5

**Description:** Run 5: args=3


**Input:**

```
3
```

**Expected Output:**

```
woensdag
werkdag
```

---

### Case 6

**Description:** Run 6: args=1


**Input:**

```
1
```

**Expected Output:**

```
maandag
werkdag
```

---

### Case 7

**Description:** Run 7: args=7


**Input:**

```
7
```

**Expected Output:**

```
zondag
weekenddag
```

---

### Case 8

**Description:** Run 8: args=8


**Input:**

```
8
```

**Expected Output:**

```
Ongeldige dag
```

---

### Case 9

**Description:** Run 9: args=5


**Input:**

```
5
```

**Expected Output:**

```
vrijdag
werkdag
```

---

### Case 10

**Description:** Run 10: args=5


**Input:**

```
5
```

**Expected Output:**

```
vrijdag
werkdag
```

---

### Case 11

**Description:** Run 11: args=6


**Input:**

```
6
```

**Expected Output:**

```
zaterdag
weekenddag
```

---

### Case 12

**Description:** Run 12: args=5


**Input:**

```
5
```

**Expected Output:**

```
vrijdag
werkdag
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
werkdag
```

---

### Case 14

**Description:** Run 14: args=3


**Input:**

```
3
```

**Expected Output:**

```
woensdag
werkdag
```

---

### Case 15

**Description:** Run 15: args=5


**Input:**

```
5
```

**Expected Output:**

```
vrijdag
werkdag
```

---
