# 03_07

Een bankautomaat vraagt de gebruiker om zijn pincode in te voeren. Als de pincode correct is (1234), vraagt de automaat om het opnamebedrag. Als het saldo (500 euro) voldoende is, wordt het geld uitgegeven en wordt het saldo verlaagd. Anders toont de automaat "Onvoldoende saldo." Als de pincode fout is, toont de automaat "Foute pincode."

Toon het nieuw saldo na de transactie.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
513
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 2

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
438
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 3

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
473
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 4

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
495
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 5

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
536
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 6

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
428
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 7

**Complete console output:**

```
Geef je pincode (4 cijfers): 1234
Geef het bedrag dat je wil opnemen: 514
Onvoldoende saldo.
```

**Input:**

```
1234
514
```

**Expected Output:**

```
Onvoldoende saldo.
```

---

### Case 8

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
559
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 9

**Complete console output:**

```
Geef je pincode (4 cijfers): 1234
Geef het bedrag dat je wil opnemen: 597
Onvoldoende saldo.
```

**Input:**

```
1234
597
```

**Expected Output:**

```
Onvoldoende saldo.
```

---

### Case 10

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
497
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 11

**Complete console output:**

```
Geef je pincode (4 cijfers): 1234
Geef het bedrag dat je wil opnemen: 583
Onvoldoende saldo.
```

**Input:**

```
1234
583
```

**Expected Output:**

```
Onvoldoende saldo.
```

---

### Case 12

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
544
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 13

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
490
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 14

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
424
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 15

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
589
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 16

**Complete console output:**

```
Geef je pincode (4 cijfers): 1234
Geef het bedrag dat je wil opnemen: 445
Uitbetaling van 445€ gaat door. Nieuw saldo: 55€
```

**Input:**

```
1234
445
```

**Expected Output:**

```
Uitbetaling van 445€ gaat door. Nieuw saldo: 55€
```

---

### Case 17

**Complete console output:**

```
Geef je pincode (4 cijfers): 1234
Geef het bedrag dat je wil opnemen: 517
Onvoldoende saldo.
```

**Input:**

```
1234
517
```

**Expected Output:**

```
Onvoldoende saldo.
```

---

### Case 18

**Complete console output:**

```
Geef je pincode (4 cijfers): 1234
Geef het bedrag dat je wil opnemen: 425
Uitbetaling van 425€ gaat door. Nieuw saldo: 75€
```

**Input:**

```
1234
425
```

**Expected Output:**

```
Uitbetaling van 425€ gaat door. Nieuw saldo: 75€
```

---

### Case 19

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

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

### Case 20

**Complete console output:**

```
Geef je pincode (4 cijfers): 1234
Geef het bedrag dat je wil opnemen: 533
Onvoldoende saldo.
```

**Input:**

```
1234
533
```

**Expected Output:**

```
Onvoldoende saldo.
```

---

### Case 21

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

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

### Case 22

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
575
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 23

**Complete console output:**

```
Geef je pincode (4 cijfers): 0147
Foute pincode.
```

**Input:**

```
0147
526
```

**Expected Output:**

```
Foute pincode.
```

---

### Case 24

**Complete console output:**

```
Geef je pincode (4 cijfers): 1234
Geef het bedrag dat je wil opnemen: 556
Onvoldoende saldo.
```

**Input:**

```
1234
556
```

**Expected Output:**

```
Onvoldoende saldo.
```

---

### Case 25

**Complete console output:**

```
Geef je pincode (4 cijfers): 1234
Geef het bedrag dat je wil opnemen: 578
Onvoldoende saldo.
```

**Input:**

```
1234
578
```

**Expected Output:**

```
Onvoldoende saldo.
```

---
