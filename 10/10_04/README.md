# 10_04

Maak een programma dat een parkeergarage simuleert. De gebruiker voert het aantal parkeerplaatsen in. Er zijn vier soorten parkeerplaatsen: kort (€2/uur), lang (€1,50/uur), gehandicapten (gratis) en laadpalen (€3/uur).

Voor elke parkeerplaats kiest de gebruiker het type en daarna het aantal ingeparkerde minuten. Een negatief aantal minuten betekent dat er geen auto's meer worden ingevoerd. Een geldig aantal minuten is nul of meer.

Na het invoeren toont het programma:
- het totaal aantal ingeparkerde auto's;
- het totale inkomen;
- het gemiddelde parkeertijd per auto (in minuten, afgerond op één decimaal).

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
3
3
15
4
-1
2
-1
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 2

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
2
3
-1
1
15
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 3

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
5
3
-1
2
0
3
-1
4
-1
4
-1
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 4

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
3
1
-1
3
30
4
60
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 5

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
1
2
60
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 6

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
1
2
15
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 7

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
2
4
30
2
60
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 8

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
5
2
60
2
-1
4
-1
4
0
1
15
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 9

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
2
3
30
3
-1
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 10

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
1
2
30
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 11

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
2
4
15
4
-1
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 12

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
1
4
0
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 13

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
2
1
60
2
-1
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 14

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
5
1
0
4
-1
4
15
4
0
4
15
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---

### Case 15

**Complete console output:**

```
NONZERO_EXIT(124): Timeout
```

**Input:**

```
2
2
0
1
-1
```

**Expected Output:**

```
NONZERO_EXIT(124): Timeout
```

---
