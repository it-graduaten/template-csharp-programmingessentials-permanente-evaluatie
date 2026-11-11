# 03_04

Een online winkel biedt de volgende kortingen aan:

- Als het aankoopbedrag meer dan 100 euro is én de klant een betalende lid is, krijgt de klant 15% korting.
- Als het aankoopbedrag meer dan 100 euro is maar de klant geen betalende lid is, krijgt de klant 5% korting.
- Als het aankoopbedrag 100 euro of minder is, krijgt de klant geen korting.

Vraag de gebruiker om het aankoopbedrag en of hij/zij een betalende lid is (ja/nee). Bereken en toon het totaalbedrag na korting.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Geef het aankoopbedrag: 129
Ben je betalende lid? (ja/nee): ja
109.65
```

**Input:**

```
129
ja
```

**Expected Output:**

```
109.65
```

---

### Case 2

**Complete console output:**

```
Geef het aankoopbedrag: 39
Ben je betalende lid? (ja/nee): ja
39.00
```

**Input:**

```
39
ja
```

**Expected Output:**

```
39.00
```

---

### Case 3

**Complete console output:**

```
Geef het aankoopbedrag: 22
Ben je betalende lid? (ja/nee): nee
22.00
```

**Input:**

```
22
nee
```

**Expected Output:**

```
22.00
```

---

### Case 4

**Complete console output:**

```
Geef het aankoopbedrag: 185
Ben je betalende lid? (ja/nee): nee
175.75
```

**Input:**

```
185
nee
```

**Expected Output:**

```
175.75
```

---

### Case 5

**Complete console output:**

```
Geef het aankoopbedrag: 104
Ben je betalende lid? (ja/nee): ja
88.40
```

**Input:**

```
104
ja
```

**Expected Output:**

```
88.40
```

---

### Case 6

**Complete console output:**

```
Geef het aankoopbedrag: 120
Ben je betalende lid? (ja/nee): nee
114.00
```

**Input:**

```
120
nee
```

**Expected Output:**

```
114.00
```

---

### Case 7

**Complete console output:**

```
Geef het aankoopbedrag: 125
Ben je betalende lid? (ja/nee): nee
118.75
```

**Input:**

```
125
nee
```

**Expected Output:**

```
118.75
```

---

### Case 8

**Complete console output:**

```
Geef het aankoopbedrag: 48
Ben je betalende lid? (ja/nee): ja
48.00
```

**Input:**

```
48
ja
```

**Expected Output:**

```
48.00
```

---

### Case 9

**Complete console output:**

```
Geef het aankoopbedrag: 24
Ben je betalende lid? (ja/nee): nee
24.00
```

**Input:**

```
24
nee
```

**Expected Output:**

```
24.00
```

---

### Case 10

**Complete console output:**

```
Geef het aankoopbedrag: 189
Ben je betalende lid? (ja/nee): nee
179.55
```

**Input:**

```
189
nee
```

**Expected Output:**

```
179.55
```

---

### Case 11

**Complete console output:**

```
Geef het aankoopbedrag: 191
Ben je betalende lid? (ja/nee): nee
181.45
```

**Input:**

```
191
nee
```

**Expected Output:**

```
181.45
```

---

### Case 12

**Complete console output:**

```
Geef het aankoopbedrag: 67
Ben je betalende lid? (ja/nee): ja
67.00
```

**Input:**

```
67
ja
```

**Expected Output:**

```
67.00
```

---

### Case 13

**Complete console output:**

```
Geef het aankoopbedrag: 2
Ben je betalende lid? (ja/nee): nee
2.00
```

**Input:**

```
2
nee
```

**Expected Output:**

```
2.00
```

---

### Case 14

**Complete console output:**

```
Geef het aankoopbedrag: 29
Ben je betalende lid? (ja/nee): ja
29.00
```

**Input:**

```
29
ja
```

**Expected Output:**

```
29.00
```

---

### Case 15

**Complete console output:**

```
Geef het aankoopbedrag: 3
Ben je betalende lid? (ja/nee): ja
3.00
```

**Input:**

```
3
ja
```

**Expected Output:**

```
3.00
```

---

### Case 16

**Complete console output:**

```
Geef het aankoopbedrag: 35
Ben je betalende lid? (ja/nee): ja
35.00
```

**Input:**

```
35
ja
```

**Expected Output:**

```
35.00
```

---

### Case 17

**Complete console output:**

```
Geef het aankoopbedrag: 76
Ben je betalende lid? (ja/nee): nee
76.00
```

**Input:**

```
76
nee
```

**Expected Output:**

```
76.00
```

---

### Case 18

**Complete console output:**

```
Geef het aankoopbedrag: 99
Ben je betalende lid? (ja/nee): ja
99.00
```

**Input:**

```
99
ja
```

**Expected Output:**

```
99.00
```

---

### Case 19

**Complete console output:**

```
Geef het aankoopbedrag: 108
Ben je betalende lid? (ja/nee): ja
91.80
```

**Input:**

```
108
ja
```

**Expected Output:**

```
91.80
```

---

### Case 20

**Complete console output:**

```
Geef het aankoopbedrag: 45
Ben je betalende lid? (ja/nee): nee
45.00
```

**Input:**

```
45
nee
```

**Expected Output:**

```
45.00
```

---

### Case 21

**Complete console output:**

```
Geef het aankoopbedrag: 175
Ben je betalende lid? (ja/nee): nee
166.25
```

**Input:**

```
175
nee
```

**Expected Output:**

```
166.25
```

---

### Case 22

**Complete console output:**

```
Geef het aankoopbedrag: 158
Ben je betalende lid? (ja/nee): ja
134.30
```

**Input:**

```
158
ja
```

**Expected Output:**

```
134.30
```

---

### Case 23

**Complete console output:**

```
Geef het aankoopbedrag: 100
Ben je betalende lid? (ja/nee): ja
100.00
```

**Input:**

```
100
ja
```

**Expected Output:**

```
100.00
```

---

### Case 24

**Complete console output:**

```
Geef het aankoopbedrag: 86
Ben je betalende lid? (ja/nee): nee
86.00
```

**Input:**

```
86
nee
```

**Expected Output:**

```
86.00
```

---

### Case 25

**Complete console output:**

```
Geef het aankoopbedrag: 47
Ben je betalende lid? (ja/nee): ja
47.00
```

**Input:**

```
47
ja
```

**Expected Output:**

```
47.00
```

---
