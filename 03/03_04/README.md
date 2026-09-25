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

**Description:** Run 1: args=180, ja


**Input:**

```
180
ja
```

**Expected Output:**

```
153
```

---

### Case 2

**Description:** Run 2: args=187, ja


**Input:**

```
187
ja
```

**Expected Output:**

```
158.95
```

---

### Case 3

**Description:** Run 3: args=51, ja


**Input:**

```
51
ja
```

**Expected Output:**

```
51
```

---

### Case 4

**Description:** Run 4: args=161, nee


**Input:**

```
161
nee
```

**Expected Output:**

```
152.95
```

---

### Case 5

**Description:** Run 5: args=102, nee


**Input:**

```
102
nee
```

**Expected Output:**

```
96.89999999999999
```

---

### Case 6

**Description:** Run 6: args=75, ja


**Input:**

```
75
ja
```

**Expected Output:**

```
75
```

---

### Case 7

**Description:** Run 7: args=52, ja


**Input:**

```
52
ja
```

**Expected Output:**

```
52
```

---

### Case 8

**Description:** Run 8: args=182, ja


**Input:**

```
182
ja
```

**Expected Output:**

```
154.7
```

---

### Case 9

**Description:** Run 9: args=14, nee


**Input:**

```
14
nee
```

**Expected Output:**

```
14
```

---

### Case 10

**Description:** Run 10: args=172, ja


**Input:**

```
172
ja
```

**Expected Output:**

```
146.2
```

---

### Case 11

**Description:** Run 11: args=129, ja


**Input:**

```
129
ja
```

**Expected Output:**

```
109.64999999999999
```

---

### Case 12

**Description:** Run 12: args=158, ja


**Input:**

```
158
ja
```

**Expected Output:**

```
134.29999999999998
```

---

### Case 13

**Description:** Run 13: args=175, ja


**Input:**

```
175
ja
```

**Expected Output:**

```
148.75
```

---

### Case 14

**Description:** Run 14: args=110, nee


**Input:**

```
110
nee
```

**Expected Output:**

```
104.5
```

---

### Case 15

**Description:** Run 15: args=62, nee


**Input:**

```
62
nee
```

**Expected Output:**

```
62
```

---

### Case 16

**Description:** Run 16: args=164, nee


**Input:**

```
164
nee
```

**Expected Output:**

```
155.79999999999998
```

---

### Case 17

**Description:** Run 17: args=93, nee


**Input:**

```
93
nee
```

**Expected Output:**

```
93
```

---

### Case 18

**Description:** Run 18: args=2, ja


**Input:**

```
2
ja
```

**Expected Output:**

```
2
```

---

### Case 19

**Description:** Run 19: args=178, nee


**Input:**

```
178
nee
```

**Expected Output:**

```
169.1
```

---

### Case 20

**Description:** Run 20: args=26, ja


**Input:**

```
26
ja
```

**Expected Output:**

```
26
```

---

### Case 21

**Description:** Run 21: args=170, nee


**Input:**

```
170
nee
```

**Expected Output:**

```
161.5
```

---

### Case 22

**Description:** Run 22: args=153, ja


**Input:**

```
153
ja
```

**Expected Output:**

```
130.04999999999998
```

---

### Case 23

**Description:** Run 23: args=173, ja


**Input:**

```
173
ja
```

**Expected Output:**

```
147.04999999999998
```

---

### Case 24

**Description:** Run 24: args=174, nee


**Input:**

```
174
nee
```

**Expected Output:**

```
165.29999999999998
```

---

### Case 25

**Description:** Run 25: args=47, ja


**Input:**

```
47
ja
```

**Expected Output:**

```
47
```

---
