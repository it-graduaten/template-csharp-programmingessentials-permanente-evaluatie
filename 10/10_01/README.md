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
Aantal deelnemers: 
2
Score 1: 
20
Score 2: 
20
Gemiddelde: 20.0
Hoogste: 20
Geslaagd: 2
```

**Input:**

```
2
20
20
```

**Expected Output:**

```
Gemiddelde: 20.0
Hoogste: 20
Geslaagd: 2
```

---

### Case 2

**Complete console output:**

```
Aantal deelnemers: 
3
Score 1: 
15
Score 2: 
5
Score 3: 
0
Gemiddelde: 6.7
Hoogste: 15
Geslaagd: 1
```

**Input:**

```
3
15
5
0
```

**Expected Output:**

```
Gemiddelde: 6.7
Hoogste: 15
Geslaagd: 1
```

---

### Case 3

**Complete console output:**

```
Aantal deelnemers: 
3
Score 1: 
10
Score 2: 
0
Score 3: 
15
Gemiddelde: 8.3
Hoogste: 15
Geslaagd: 2
```

**Input:**

```
3
10
0
15
```

**Expected Output:**

```
Gemiddelde: 8.3
Hoogste: 15
Geslaagd: 2
```

---

### Case 4

**Complete console output:**

```
Aantal deelnemers: 
2
Score 1: 
9
Score 2: 
0
Gemiddelde: 4.5
Hoogste: 9
Geslaagd: 0
```

**Input:**

```
2
9
0
```

**Expected Output:**

```
Gemiddelde: 4.5
Hoogste: 9
Geslaagd: 0
```

---

### Case 5

**Complete console output:**

```
Aantal deelnemers: 
2
Score 1: 
17
Score 2: 
5
Gemiddelde: 11.0
Hoogste: 17
Geslaagd: 1
```

**Input:**

```
2
17
5
```

**Expected Output:**

```
Gemiddelde: 11.0
Hoogste: 17
Geslaagd: 1
```

---

### Case 6

**Complete console output:**

```
Aantal deelnemers: 
2
Score 1: 
20
Score 2: 
20
Gemiddelde: 20.0
Hoogste: 20
Geslaagd: 2
```

**Input:**

```
2
20
20
```

**Expected Output:**

```
Gemiddelde: 20.0
Hoogste: 20
Geslaagd: 2
```

---

### Case 7

**Complete console output:**

```
Aantal deelnemers: 
3
Score 1: 
10
Score 2: 
9
Score 3: 
15
Gemiddelde: 11.3
Hoogste: 15
Geslaagd: 2
```

**Input:**

```
3
10
9
15
```

**Expected Output:**

```
Gemiddelde: 11.3
Hoogste: 15
Geslaagd: 2
```

---

### Case 8

**Complete console output:**

```
Aantal deelnemers: 
5
Score 1: 
9
Score 2: 
20
Score 3: 
15
Score 4: 
20
Score 5: 
0
Gemiddelde: 12.8
Hoogste: 20
Geslaagd: 3
```

**Input:**

```
5
9
20
15
20
0
```

**Expected Output:**

```
Gemiddelde: 12.8
Hoogste: 20
Geslaagd: 3
```

---

### Case 9

**Complete console output:**

```
Aantal deelnemers: 
1
Score 1: 
9
Gemiddelde: 9.0
Hoogste: 9
Geslaagd: 0
```

**Input:**

```
1
9
```

**Expected Output:**

```
Gemiddelde: 9.0
Hoogste: 9
Geslaagd: 0
```

---

### Case 10

**Complete console output:**

```
Aantal deelnemers: 
2
Score 1: 
9
Score 2: 
10
Gemiddelde: 9.5
Hoogste: 10
Geslaagd: 1
```

**Input:**

```
2
9
10
```

**Expected Output:**

```
Gemiddelde: 9.5
Hoogste: 10
Geslaagd: 1
```

---

### Case 11

**Complete console output:**

```
Aantal deelnemers: 
2
Score 1: 
20
Score 2: 
0
Gemiddelde: 10.0
Hoogste: 20
Geslaagd: 1
```

**Input:**

```
2
20
0
```

**Expected Output:**

```
Gemiddelde: 10.0
Hoogste: 20
Geslaagd: 1
```

---

### Case 12

**Complete console output:**

```
Aantal deelnemers: 
1
Score 1: 
5
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
Gemiddelde: 5.0
Hoogste: 5
Geslaagd: 0
```

---

### Case 13

**Complete console output:**

```
Aantal deelnemers: 
1
Score 1: 
5
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
Gemiddelde: 5.0
Hoogste: 5
Geslaagd: 0
```

---

### Case 14

**Complete console output:**

```
Aantal deelnemers: 
3
Score 1: 
20
Score 2: 
20
Score 3: 
9
Gemiddelde: 16.3
Hoogste: 20
Geslaagd: 2
```

**Input:**

```
3
20
20
9
```

**Expected Output:**

```
Gemiddelde: 16.3
Hoogste: 20
Geslaagd: 2
```

---

### Case 15

**Complete console output:**

```
Aantal deelnemers: 
5
Score 1: 
0
Score 2: 
15
Score 3: 
20
Score 4: 
5
Score 5: 
15
Gemiddelde: 11.0
Hoogste: 20
Geslaagd: 3
```

**Input:**

```
5
0
15
20
5
15
```

**Expected Output:**

```
Gemiddelde: 11.0
Hoogste: 20
Geslaagd: 3
```

---
