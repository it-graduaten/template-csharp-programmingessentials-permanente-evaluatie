# 10_01

Maak een programma dat de scores van een quiz verwerkt. De gebruiker voert het aantal deelnemers in en daarna voor elke deelnemer de score. Een geldige score ligt tussen 0 en 20. Ongeldige scores moeten opnieuw gevraagd worden.

Na het invoeren toont het programma:
- het gemiddelde;
- de hoogste score;
- het aantal geslaagde deelnemers (een score van 10 of meer is geslaagd).

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Aantal deelnemers: Score 1: 3
Score 2: 17
Score 3: 15
Gemiddelde: 13.7
Hoogste: 17
Geslaagd: 2
```

**Input:**

```
3
17
15
9
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 13.7
Hoogste: 17
Geslaagd: 2
```

---

### Case 2

**Complete console output:**

```
Aantal deelnemers: Score 1: 5
Score 2: 0
Score 3: 20
Score 4: 10
Score 5: 10
Gemiddelde: 9.8
Hoogste: 20
Geslaagd: 3
```

**Input:**

```
5
0
20
10
10
9
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 9.8
Hoogste: 20
Geslaagd: 3
```

---

### Case 3

**Complete console output:**

```
Aantal deelnemers: Score 1: 1
Gemiddelde: 5.0
Hoogste: 5
Geslaagd: 0
```

**Input:**

```
1
5
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 5.0
Hoogste: 5
Geslaagd: 0
```

---

### Case 4

**Complete console output:**

```
Aantal deelnemers: Score 1: 5
Score 2: 5
Score 3: 15
Score 4: 0
Score 5: 9
Gemiddelde: 9.2
Hoogste: 17
Geslaagd: 2
```

**Input:**

```
5
5
15
0
9
17
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 9.2
Hoogste: 17
Geslaagd: 2
```

---

### Case 5

**Complete console output:**

```
Aantal deelnemers: Score 1: 2
Score 2: 9
Gemiddelde: 14.5
Hoogste: 20
Geslaagd: 1
```

**Input:**

```
2
9
20
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 14.5
Hoogste: 20
Geslaagd: 1
```

---

### Case 6

**Complete console output:**

```
Aantal deelnemers: Score 1: 5
Score 2: 17
Score 3: 20
Score 4: 9
Score 5: 5
Gemiddelde: 11.2
Hoogste: 20
Geslaagd: 2
```

**Input:**

```
5
17
20
9
5
5
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 11.2
Hoogste: 20
Geslaagd: 2
```

---

### Case 7

**Complete console output:**

```
Aantal deelnemers: Score 1: 3
Score 2: 15
Score 3: 20
Gemiddelde: 11.7
Hoogste: 20
Geslaagd: 2
```

**Input:**

```
3
15
20
0
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 11.7
Hoogste: 20
Geslaagd: 2
```

---

### Case 8

**Complete console output:**

```
Aantal deelnemers: Score 1: 3
Score 2: 15
Score 3: 15
Gemiddelde: 16.7
Hoogste: 20
Geslaagd: 3
```

**Input:**

```
3
15
15
20
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 16.7
Hoogste: 20
Geslaagd: 3
```

---

### Case 9

**Complete console output:**

```
Aantal deelnemers: Score 1: 5
Score 2: 17
Score 3: 10
Score 4: 5
Score 5: 5
Gemiddelde: 7.4
Hoogste: 17
Geslaagd: 2
```

**Input:**

```
5
17
10
5
5
0
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 7.4
Hoogste: 17
Geslaagd: 2
```

---

### Case 10

**Complete console output:**

```
Aantal deelnemers: Score 1: 5
Score 2: 5
Score 3: 15
Score 4: 17
Score 5: 9
Gemiddelde: 11.2
Hoogste: 17
Geslaagd: 3
```

**Input:**

```
5
5
15
17
9
10
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 11.2
Hoogste: 17
Geslaagd: 3
```

---

### Case 11

**Complete console output:**

```
Aantal deelnemers: Score 1: 1
Gemiddelde: 0.0
Hoogste: 0
Geslaagd: 0
```

**Input:**

```
1
0
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 0.0
Hoogste: 0
Geslaagd: 0
```

---

### Case 12

**Complete console output:**

```
Aantal deelnemers: Score 1: 1
Gemiddelde: 15.0
Hoogste: 15
Geslaagd: 1
```

**Input:**

```
1
15
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 15.0
Hoogste: 15
Geslaagd: 1
```

---

### Case 13

**Complete console output:**

```
Aantal deelnemers: Score 1: 2
Score 2: 9
Gemiddelde: 14.5
Hoogste: 20
Geslaagd: 1
```

**Input:**

```
2
9
20
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 14.5
Hoogste: 20
Geslaagd: 1
```

---

### Case 14

**Complete console output:**

```
Aantal deelnemers: Score 1: 1
Gemiddelde: 5.0
Hoogste: 5
Geslaagd: 0
```

**Input:**

```
1
5
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 5.0
Hoogste: 5
Geslaagd: 0
```

---

### Case 15

**Complete console output:**

```
Aantal deelnemers: Score 1: 1
Gemiddelde: 15.0
Hoogste: 15
Geslaagd: 1
```

**Input:**

```
1
15
```

**Expected Output:**

```
Aantal deelnemers: Gemiddelde: 15.0
Hoogste: 15
Geslaagd: 1
```

---
