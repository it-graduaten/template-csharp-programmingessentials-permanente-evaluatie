# 10_03

Maak een programma dat de resultaten van een stemverkiezing verwerkt. De gebruiker voert het aantal kiezers in en daarna voor elke kiezer de stem (een getal tussen 1 en 5, elk getal vertegenwoordigt een partij). Ongeldige stemmen moeten opnieuw gevraagd worden.

Na het invoeren toont het programma:
- het totaal aantal geldige stemmen;
- het aantal stemmen per partij (partij 1 tot en met partij 5);
- de partij met de meeste stemmen;
- het percentage van de winnende partij (afgerond op één decimaal).

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Aantal kiezers: Stem 1: 3
Stem 2: 5
Stem 3: 5
Totaal: 3
Partij 1: 0
Partij 2: 0
Partij 3: 1
Partij 4: 0
Partij 5: 2
Winnende partij: 5
Percentage: 66.7%
```

**Input:**

```
3
5
5
3
```

**Expected Output:**

```
Aantal kiezers: Totaal: 3
Partij 1: 0
Partij 2: 0
Partij 3: 1
Partij 4: 0
Partij 5: 2
Winnende partij: 5
Percentage: 66.7%
```

---

### Case 2

**Complete console output:**

```
Aantal kiezers: Stem 1: 2
Stem 2: 4
Totaal: 2
Partij 1: 1
Partij 2: 0
Partij 3: 0
Partij 4: 1
Partij 5: 0
Winnende partij: 1
Percentage: 50.0%
```

**Input:**

```
2
4
1
```

**Expected Output:**

```
Aantal kiezers: Totaal: 2
Partij 1: 1
Partij 2: 0
Partij 3: 0
Partij 4: 1
Partij 5: 0
Winnende partij: 1
Percentage: 50.0%
```

---

### Case 3

**Complete console output:**

```
Aantal kiezers: Stem 1: 5
Stem 2: 3
Stem 3: 5
Stem 4: 1
Stem 5: 5
Totaal: 5
Partij 1: 2
Partij 2: 0
Partij 3: 1
Partij 4: 0
Partij 5: 2
Winnende partij: 1
Percentage: 40.0%
```

**Input:**

```
5
3
5
1
5
1
```

**Expected Output:**

```
Aantal kiezers: Totaal: 5
Partij 1: 2
Partij 2: 0
Partij 3: 1
Partij 4: 0
Partij 5: 2
Winnende partij: 1
Percentage: 40.0%
```

---

### Case 4

**Complete console output:**

```
Aantal kiezers: Stem 1: 2
Stem 2: 5
Totaal: 2
Partij 1: 1
Partij 2: 0
Partij 3: 0
Partij 4: 0
Partij 5: 1
Winnende partij: 1
Percentage: 50.0%
```

**Input:**

```
2
5
1
```

**Expected Output:**

```
Aantal kiezers: Totaal: 2
Partij 1: 1
Partij 2: 0
Partij 3: 0
Partij 4: 0
Partij 5: 1
Winnende partij: 1
Percentage: 50.0%
```

---

### Case 5

**Complete console output:**

```
Aantal kiezers: Stem 1: 5
Stem 2: 4
Stem 3: 3
Stem 4: 5
Stem 5: 5
Totaal: 5
Partij 1: 0
Partij 2: 1
Partij 3: 1
Partij 4: 1
Partij 5: 2
Winnende partij: 5
Percentage: 40.0%
```

**Input:**

```
5
4
3
5
5
2
```

**Expected Output:**

```
Aantal kiezers: Totaal: 5
Partij 1: 0
Partij 2: 1
Partij 3: 1
Partij 4: 1
Partij 5: 2
Winnende partij: 5
Percentage: 40.0%
```

---

### Case 6

**Complete console output:**

```
Aantal kiezers: Stem 1: 1
Totaal: 1
Partij 1: 0
Partij 2: 0
Partij 3: 1
Partij 4: 0
Partij 5: 0
Winnende partij: 3
Percentage: 100.0%
```

**Input:**

```
1
3
```

**Expected Output:**

```
Aantal kiezers: Totaal: 1
Partij 1: 0
Partij 2: 0
Partij 3: 1
Partij 4: 0
Partij 5: 0
Winnende partij: 3
Percentage: 100.0%
```

---

### Case 7

**Complete console output:**

```
Aantal kiezers: Stem 1: 2
Stem 2: 2
Totaal: 2
Partij 1: 0
Partij 2: 1
Partij 3: 1
Partij 4: 0
Partij 5: 0
Winnende partij: 2
Percentage: 50.0%
```

**Input:**

```
2
2
3
```

**Expected Output:**

```
Aantal kiezers: Totaal: 2
Partij 1: 0
Partij 2: 1
Partij 3: 1
Partij 4: 0
Partij 5: 0
Winnende partij: 2
Percentage: 50.0%
```

---

### Case 8

**Complete console output:**

```
Aantal kiezers: Stem 1: 5
Stem 2: 1
Stem 3: 4
Stem 4: 3
Stem 5: 2
Totaal: 5
Partij 1: 1
Partij 2: 1
Partij 3: 2
Partij 4: 1
Partij 5: 0
Winnende partij: 3
Percentage: 40.0%
```

**Input:**

```
5
1
4
3
2
3
```

**Expected Output:**

```
Aantal kiezers: Totaal: 5
Partij 1: 1
Partij 2: 1
Partij 3: 2
Partij 4: 1
Partij 5: 0
Winnende partij: 3
Percentage: 40.0%
```

---

### Case 9

**Complete console output:**

```
Aantal kiezers: Stem 1: 1
Totaal: 1
Partij 1: 0
Partij 2: 0
Partij 3: 0
Partij 4: 1
Partij 5: 0
Winnende partij: 4
Percentage: 100.0%
```

**Input:**

```
1
4
```

**Expected Output:**

```
Aantal kiezers: Totaal: 1
Partij 1: 0
Partij 2: 0
Partij 3: 0
Partij 4: 1
Partij 5: 0
Winnende partij: 4
Percentage: 100.0%
```

---

### Case 10

**Complete console output:**

```
Aantal kiezers: Stem 1: 5
Stem 2: 2
Stem 3: 2
Stem 4: 4
Stem 5: 1
Totaal: 5
Partij 1: 1
Partij 2: 2
Partij 3: 0
Partij 4: 2
Partij 5: 0
Winnende partij: 2
Percentage: 40.0%
```

**Input:**

```
5
2
2
4
1
4
```

**Expected Output:**

```
Aantal kiezers: Totaal: 5
Partij 1: 1
Partij 2: 2
Partij 3: 0
Partij 4: 2
Partij 5: 0
Winnende partij: 2
Percentage: 40.0%
```

---

### Case 11

**Complete console output:**

```
Aantal kiezers: Stem 1: 5
Stem 2: 4
Stem 3: 2
Stem 4: 5
Stem 5: 1
Totaal: 5
Partij 1: 1
Partij 2: 2
Partij 3: 0
Partij 4: 1
Partij 5: 1
Winnende partij: 2
Percentage: 40.0%
```

**Input:**

```
5
4
2
5
1
2
```

**Expected Output:**

```
Aantal kiezers: Totaal: 5
Partij 1: 1
Partij 2: 2
Partij 3: 0
Partij 4: 1
Partij 5: 1
Winnende partij: 2
Percentage: 40.0%
```

---

### Case 12

**Complete console output:**

```
Aantal kiezers: Stem 1: 2
Stem 2: 2
Totaal: 2
Partij 1: 0
Partij 2: 2
Partij 3: 0
Partij 4: 0
Partij 5: 0
Winnende partij: 2
Percentage: 100.0%
```

**Input:**

```
2
2
2
```

**Expected Output:**

```
Aantal kiezers: Totaal: 2
Partij 1: 0
Partij 2: 2
Partij 3: 0
Partij 4: 0
Partij 5: 0
Winnende partij: 2
Percentage: 100.0%
```

---

### Case 13

**Complete console output:**

```
Aantal kiezers: Stem 1: 1
Totaal: 1
Partij 1: 1
Partij 2: 0
Partij 3: 0
Partij 4: 0
Partij 5: 0
Winnende partij: 1
Percentage: 100.0%
```

**Input:**

```
1
1
```

**Expected Output:**

```
Aantal kiezers: Totaal: 1
Partij 1: 1
Partij 2: 0
Partij 3: 0
Partij 4: 0
Partij 5: 0
Winnende partij: 1
Percentage: 100.0%
```

---

### Case 14

**Complete console output:**

```
Aantal kiezers: Stem 1: 2
Stem 2: 1
Totaal: 2
Partij 1: 1
Partij 2: 0
Partij 3: 0
Partij 4: 0
Partij 5: 1
Winnende partij: 1
Percentage: 50.0%
```

**Input:**

```
2
1
5
```

**Expected Output:**

```
Aantal kiezers: Totaal: 2
Partij 1: 1
Partij 2: 0
Partij 3: 0
Partij 4: 0
Partij 5: 1
Winnende partij: 1
Percentage: 50.0%
```

---

### Case 15

**Complete console output:**

```
Aantal kiezers: Stem 1: 5
Stem 2: 4
Stem 3: 2
Stem 4: 2
Stem 5: 5
Totaal: 5
Partij 1: 0
Partij 2: 3
Partij 3: 0
Partij 4: 1
Partij 5: 1
Winnende partij: 2
Percentage: 60.0%
```

**Input:**

```
5
4
2
2
5
2
```

**Expected Output:**

```
Aantal kiezers: Totaal: 5
Partij 1: 0
Partij 2: 3
Partij 3: 0
Partij 4: 1
Partij 5: 1
Winnende partij: 2
Percentage: 60.0%
```

---
