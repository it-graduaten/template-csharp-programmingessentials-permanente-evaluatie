# 03_07

Een bankautomaat vraagt de gebruiker om zijn pincode in te voeren. Als de pincode correct is (1234), vraagt de automaat om het opnamebedrag. Als het saldo (500 euro) voldoende is, wordt het geld uitgegeven en wordt het saldo verlaagd. Anders toont de automaat "Onvoldoende saldo." Als de pincode fout is, toont de automaat "Foute pincode."

Toon het nieuw saldo na de transactie.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Description:** Run 1: args=0147, 579


**Input:**

```
0147
579
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 2

**Description:** Run 2: args=1234, 570


**Input:**

```
1234
570
```

**Expected Output:**

```
Onvoldoende saldo.
```

---

### Case 3

**Description:** Run 3: args=0147, 502


**Input:**

```
0147
502
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 4

**Description:** Run 4: args=0147, 529


**Input:**

```
0147
529
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 5

**Description:** Run 5: args=0147, 433


**Input:**

```
0147
433
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 6

**Description:** Run 6: args=1234, 479


**Input:**

```
1234
479
```

**Expected Output:**

```
Uitbetaling van 479€ gaat door. Nieuw saldo: 21€
```

---

### Case 7

**Description:** Run 7: args=1234, 531


**Input:**

```
1234
531
```

**Expected Output:**

```
Onvoldoende saldo.
```

---

### Case 8

**Description:** Run 8: args=1234, 487


**Input:**

```
1234
487
```

**Expected Output:**

```
Uitbetaling van 487€ gaat door. Nieuw saldo: 13€
```

---

### Case 9

**Description:** Run 9: args=1234, 436


**Input:**

```
1234
436
```

**Expected Output:**

```
Uitbetaling van 436€ gaat door. Nieuw saldo: 64€
```

---

### Case 10

**Description:** Run 10: args=0147, 546


**Input:**

```
0147
546
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 11

**Description:** Run 11: args=1234, 412


**Input:**

```
1234
412
```

**Expected Output:**

```
Uitbetaling van 412€ gaat door. Nieuw saldo: 88€
```

---

### Case 12

**Description:** Run 12: args=1234, 530


**Input:**

```
1234
530
```

**Expected Output:**

```
Onvoldoende saldo.
```

---

### Case 13

**Description:** Run 13: args=1234, 515


**Input:**

```
1234
515
```

**Expected Output:**

```
Onvoldoende saldo.
```

---

### Case 14

**Description:** Run 14: args=0147, 531


**Input:**

```
0147
531
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 15

**Description:** Run 15: args=0147, 518


**Input:**

```
0147
518
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 16

**Description:** Run 16: args=0147, 502


**Input:**

```
0147
502
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 17

**Description:** Run 17: args=1234, 548


**Input:**

```
1234
548
```

**Expected Output:**

```
Onvoldoende saldo.
```

---

### Case 18

**Description:** Run 18: args=0147, 460


**Input:**

```
0147
460
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 19

**Description:** Run 19: args=1234, 441


**Input:**

```
1234
441
```

**Expected Output:**

```
Uitbetaling van 441€ gaat door. Nieuw saldo: 59€
```

---

### Case 20

**Description:** Run 20: args=0147, 547


**Input:**

```
0147
547
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 21

**Description:** Run 21: args=1234, 458


**Input:**

```
1234
458
```

**Expected Output:**

```
Uitbetaling van 458€ gaat door. Nieuw saldo: 42€
```

---

### Case 22

**Description:** Run 22: args=0147, 499


**Input:**

```
0147
499
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 23

**Description:** Run 23: args=0147, 431


**Input:**

```
0147
431
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 24

**Description:** Run 24: args=1234, 592


**Input:**

```
1234
592
```

**Expected Output:**

```
Onvoldoende saldo.
```

---

### Case 25

**Description:** Run 25: args=1234, 486


**Input:**

```
1234
486
```

**Expected Output:**

```
Uitbetaling van 486€ gaat door. Nieuw saldo: 14€
```

---
