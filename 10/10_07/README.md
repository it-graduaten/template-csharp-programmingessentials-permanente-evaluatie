# 10_07

Maak een programma dat de boekverkoop van een bibliotheek bijhoudt. De gebruiker voert het aantal verkochte boeken in en daarna voor elk boek de prijs. Een geldige prijs is groter dan 0. Ongeldige prijzen moeten opnieuw gevraagd worden.

Na het invoeren toont het programma:
- het totaal aantal boeken;
- het totaalbedrag;
- het gemiddelde boekprijs;
- het duurste boek;
- het goedkoopste boek.

Daarna kan de gebruiker een prijs ingeven. Het programma toont hoeveel boeken exact die prijs hebben.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 1
Totaal boeken: 1
Totaalbedrag: 1
Gemiddelde prijs: 1.0
Duurst: 1
Goedkoopst: 1
Gezochte prijs: 1
Aantal boeken met 20: 0
```

**Input:**

```
1
1
20
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 1
Totaalbedrag: 1
Gemiddelde prijs: 1.0
Duurst: 1
Goedkoopst: 1
Aantal boeken met 20: 0
```

---

### Case 2

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 2
Prijs boek 2: 20
Totaal boeken: 2
Totaalbedrag: 25
Gemiddelde prijs: 12.5
Duurst: 20
Goedkoopst: 5
Gezochte prijs: 5
Aantal boeken met 99: 0
```

**Input:**

```
2
20
5
99
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 2
Totaalbedrag: 25
Gemiddelde prijs: 12.5
Duurst: 20
Goedkoopst: 5
Aantal boeken met 99: 0
```

---

### Case 3

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 5
Prijs boek 2: 20
Prijs boek 3: 10
Prijs boek 4: 25
Prijs boek 5: 5
Totaal boeken: 5
Totaalbedrag: 61
Gemiddelde prijs: 12.2
Duurst: 25
Goedkoopst: 1
Gezochte prijs: 1
Aantal boeken met 5: 1
```

**Input:**

```
5
20
10
25
5
1
5
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 5
Totaalbedrag: 61
Gemiddelde prijs: 12.2
Duurst: 25
Goedkoopst: 1
Aantal boeken met 5: 1
```

---

### Case 4

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 5
Prijs boek 2: 15
Prijs boek 3: 10
Prijs boek 4: 20
Prijs boek 5: 20
Totaal boeken: 5
Totaalbedrag: 80
Gemiddelde prijs: 16.0
Duurst: 20
Goedkoopst: 10
Gezochte prijs: 15
Aantal boeken met 10: 1
```

**Input:**

```
5
15
10
20
20
15
10
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 5
Totaalbedrag: 80
Gemiddelde prijs: 16.0
Duurst: 20
Goedkoopst: 10
Aantal boeken met 10: 1
```

---

### Case 5

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 2
Prijs boek 2: 10
Totaal boeken: 2
Totaalbedrag: 30
Gemiddelde prijs: 15.0
Duurst: 20
Goedkoopst: 10
Gezochte prijs: 20
Aantal boeken met 1: 0
```

**Input:**

```
2
10
20
1
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 2
Totaalbedrag: 30
Gemiddelde prijs: 15.0
Duurst: 20
Goedkoopst: 10
Aantal boeken met 1: 0
```

---

### Case 6

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 1
Totaal boeken: 1
Totaalbedrag: 20
Gemiddelde prijs: 20.0
Duurst: 20
Goedkoopst: 20
Gezochte prijs: 20
Aantal boeken met 15: 0
```

**Input:**

```
1
20
15
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 1
Totaalbedrag: 20
Gemiddelde prijs: 20.0
Duurst: 20
Goedkoopst: 20
Aantal boeken met 15: 0
```

---

### Case 7

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 5
Prijs boek 2: 10
Prijs boek 3: 25
Prijs boek 4: 20
Prijs boek 5: 20
Totaal boeken: 5
Totaalbedrag: 90
Gemiddelde prijs: 18.0
Duurst: 25
Goedkoopst: 10
Gezochte prijs: 15
Aantal boeken met 20: 2
```

**Input:**

```
5
10
25
20
20
15
20
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 5
Totaalbedrag: 90
Gemiddelde prijs: 18.0
Duurst: 25
Goedkoopst: 10
Aantal boeken met 20: 2
```

---

### Case 8

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 5
Prijs boek 2: 10
Prijs boek 3: 5
Prijs boek 4: 10
Prijs boek 5: 15
Totaal boeken: 5
Totaalbedrag: 50
Gemiddelde prijs: 10.0
Duurst: 15
Goedkoopst: 5
Gezochte prijs: 10
Aantal boeken met 1: 0
```

**Input:**

```
5
10
5
10
15
10
1
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 5
Totaalbedrag: 50
Gemiddelde prijs: 10.0
Duurst: 15
Goedkoopst: 5
Aantal boeken met 1: 0
```

---

### Case 9

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 3
Prijs boek 2: 20
Prijs boek 3: 1
Totaal boeken: 3
Totaalbedrag: 46
Gemiddelde prijs: 15.3
Duurst: 25
Goedkoopst: 1
Gezochte prijs: 25
Aantal boeken met 99: 0
```

**Input:**

```
3
20
1
25
99
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 3
Totaalbedrag: 46
Gemiddelde prijs: 15.3
Duurst: 25
Goedkoopst: 1
Aantal boeken met 99: 0
```

---

### Case 10

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 1
Totaal boeken: 1
Totaalbedrag: 20
Gemiddelde prijs: 20.0
Duurst: 20
Goedkoopst: 20
Gezochte prijs: 20
Aantal boeken met 5: 0
```

**Input:**

```
1
20
5
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 1
Totaalbedrag: 20
Gemiddelde prijs: 20.0
Duurst: 20
Goedkoopst: 20
Aantal boeken met 5: 0
```

---

### Case 11

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 1
Totaal boeken: 1
Totaalbedrag: 5
Gemiddelde prijs: 5.0
Duurst: 5
Goedkoopst: 5
Gezochte prijs: 5
Aantal boeken met 99: 0
```

**Input:**

```
1
5
99
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 1
Totaalbedrag: 5
Gemiddelde prijs: 5.0
Duurst: 5
Goedkoopst: 5
Aantal boeken met 99: 0
```

---

### Case 12

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 3
Prijs boek 2: 20
Prijs boek 3: 25
Totaal boeken: 3
Totaalbedrag: 55
Gemiddelde prijs: 18.3
Duurst: 25
Goedkoopst: 10
Gezochte prijs: 10
Aantal boeken met 5: 0
```

**Input:**

```
3
20
25
10
5
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 3
Totaalbedrag: 55
Gemiddelde prijs: 18.3
Duurst: 25
Goedkoopst: 10
Aantal boeken met 5: 0
```

---

### Case 13

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 1
Totaal boeken: 1
Totaalbedrag: 10
Gemiddelde prijs: 10.0
Duurst: 10
Goedkoopst: 10
Gezochte prijs: 10
Aantal boeken met 99: 0
```

**Input:**

```
1
10
99
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 1
Totaalbedrag: 10
Gemiddelde prijs: 10.0
Duurst: 10
Goedkoopst: 10
Aantal boeken met 99: 0
```

---

### Case 14

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 5
Prijs boek 2: 15
Prijs boek 3: 20
Prijs boek 4: 20
Prijs boek 5: 15
Totaal boeken: 5
Totaalbedrag: 90
Gemiddelde prijs: 18.0
Duurst: 20
Goedkoopst: 15
Gezochte prijs: 20
Aantal boeken met 15: 2
```

**Input:**

```
5
15
20
20
15
20
15
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 5
Totaalbedrag: 90
Gemiddelde prijs: 18.0
Duurst: 20
Goedkoopst: 15
Aantal boeken met 15: 2
```

---

### Case 15

**Complete console output:**

```
Aantal boeken: Prijs boek 1: 2
Prijs boek 2: 1
Totaal boeken: 2
Totaalbedrag: 6
Gemiddelde prijs: 3.0
Duurst: 5
Goedkoopst: 1
Gezochte prijs: 5
Aantal boeken met 1: 1
```

**Input:**

```
2
1
5
1
```

**Expected Output:**

```
Aantal boeken: Totaal boeken: 2
Totaalbedrag: 6
Gemiddelde prijs: 3.0
Duurst: 5
Goedkoopst: 1
Aantal boeken met 1: 1
```

---
