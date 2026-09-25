# 03_05

Een school hanteert de volgende regels voor het toekennen van een studierichting:

- Als de student gemiddeld 75% of meer haalt én wiskunde heeft gevolgd, kan de student kiezen voor de richting "Wetenschap".
- Als de student gemiddeld 75% of meer haalt maar wiskunde niet heeft gevolgd, kan de student kiezen voor de richting "Letteren".
- Als de student gemiddeld tussen 60% en 74% haalt, wordt de student doorverwezen naar de richting "Techniek".
- Als de student minder dan 60% haalt, wordt de student doorverwezen naar de richtingskeuzebegeleiding.

Vraag de gebruiker om zijn gemiddelde percentage en of hij/zij wiskunde heeft gevolgd (ja/nee). Toon de aanbevolen studierichting.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Description:** Run 1: args=41, ja


**Input:**

```
41
ja
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 2

**Description:** Run 2: args=15, ja


**Input:**

```
15
ja
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 3

**Description:** Run 3: args=10, ja


**Input:**

```
10
ja
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 4

**Description:** Run 4: args=27, nee


**Input:**

```
27
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 5

**Description:** Run 5: args=11, nee


**Input:**

```
11
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 6

**Description:** Run 6: args=15, nee


**Input:**

```
15
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 7

**Description:** Run 7: args=69, nee


**Input:**

```
69
nee
```

**Expected Output:**

```
Techniek
```

---

### Case 8

**Description:** Run 8: args=19, nee


**Input:**

```
19
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 9

**Description:** Run 9: args=13, ja


**Input:**

```
13
ja
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 10

**Description:** Run 10: args=36, nee


**Input:**

```
36
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 11

**Description:** Run 11: args=48, nee


**Input:**

```
48
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 12

**Description:** Run 12: args=4, nee


**Input:**

```
4
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 13

**Description:** Run 13: args=94, ja


**Input:**

```
94
ja
```

**Expected Output:**

```
Wetenschap
```

---

### Case 14

**Description:** Run 14: args=51, nee


**Input:**

```
51
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 15

**Description:** Run 15: args=40, ja


**Input:**

```
40
ja
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 16

**Description:** Run 16: args=32, ja


**Input:**

```
32
ja
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 17

**Description:** Run 17: args=29, nee


**Input:**

```
29
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 18

**Description:** Run 18: args=93, ja


**Input:**

```
93
ja
```

**Expected Output:**

```
Wetenschap
```

---

### Case 19

**Description:** Run 19: args=7, ja


**Input:**

```
7
ja
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 20

**Description:** Run 20: args=25, ja


**Input:**

```
25
ja
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 21

**Description:** Run 21: args=12, nee


**Input:**

```
12
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 22

**Description:** Run 22: args=39, nee


**Input:**

```
39
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 23

**Description:** Run 23: args=89, nee


**Input:**

```
89
nee
```

**Expected Output:**

```
Letteren
```

---

### Case 24

**Description:** Run 24: args=36, nee


**Input:**

```
36
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 25

**Description:** Run 25: args=3, nee


**Input:**

```
3
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---
