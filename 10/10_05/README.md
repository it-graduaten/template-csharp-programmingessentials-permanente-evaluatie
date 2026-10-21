# 10_05

Maak een programma dat de resultaten van een sportwedstrijd verwerkt. De gebruiker voert het aantal deelnemers in en daarna voor elke deelnemer de tijd in seconden. Een geldige tijd is groter dan 0. Ongeldige tijden moeten opnieuw gevraagd worden.

Na het invoeren toont het programma:
- de snelste tijd;
- de langzaamste tijd;
- het gemiddelde;
- het aantal deelnemers dat sneller was dan het gemiddelde;
- de ranglijst van de top 3 snelste deelnemers (deelnemer nummer en tijd).

Daarna kan de gebruiker een specifieke tijd ingeven. Het programma toont hoeveel deelnemers exact die tijd hebben behaald.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 1
Snelste: 200
Langzaamste: 200
Gemiddelde: 200.0
Sneller dan gemiddelde: 0
Top 3:
1: 200
Gezochte tijd: 200
Aantal deelnemers met 10s: 0
```

**Input:**

```
1
200
10
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 200
Langzaamste: 200
Gemiddelde: 200.0
Sneller dan gemiddelde: 0
Top 3:
1: 200
Aantal deelnemers met 10s: 0
```

---

### Case 2

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 5
Tijd 2: 200
Tijd 3: 60
Tijd 4: 1
Tijd 5: 30
Snelste: 1
Langzaamste: 200
Gemiddelde: 58.4
Sneller dan gemiddelde: 3
Top 3:
3: 1
5: 1
4: 30
Gezochte tijd: 1
Aantal deelnemers met 1s: 2
```

**Input:**

```
5
200
60
1
30
1
1
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 1
Langzaamste: 200
Gemiddelde: 58.4
Sneller dan gemiddelde: 3
Top 3:
3: 1
5: 1
4: 30
Aantal deelnemers met 1s: 2
```

---

### Case 3

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 1
Snelste: 30
Langzaamste: 30
Gemiddelde: 30.0
Sneller dan gemiddelde: 0
Top 3:
1: 30
Gezochte tijd: 30
Aantal deelnemers met 999s: 0
```

**Input:**

```
1
30
999
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 30
Langzaamste: 30
Gemiddelde: 30.0
Sneller dan gemiddelde: 0
Top 3:
1: 30
Aantal deelnemers met 999s: 0
```

---

### Case 4

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 3
Tijd 2: 200
Tijd 3: 10
Snelste: 10
Langzaamste: 200
Gemiddelde: 136.7
Sneller dan gemiddelde: 1
Top 3:
2: 10
1: 200
3: 200
Gezochte tijd: 200
Aantal deelnemers met 200s: 2
```

**Input:**

```
3
200
10
200
200
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 10
Langzaamste: 200
Gemiddelde: 136.7
Sneller dan gemiddelde: 1
Top 3:
2: 10
1: 200
3: 200
Aantal deelnemers met 200s: 2
```

---

### Case 5

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 3
Tijd 2: 1
Tijd 3: 100
Snelste: 1
Langzaamste: 100
Gemiddelde: 53.7
Sneller dan gemiddelde: 1
Top 3:
1: 1
3: 60
2: 100
Gezochte tijd: 60
Aantal deelnemers met 100s: 1
```

**Input:**

```
3
1
100
60
100
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 1
Langzaamste: 100
Gemiddelde: 53.7
Sneller dan gemiddelde: 1
Top 3:
1: 1
3: 60
2: 100
Aantal deelnemers met 100s: 1
```

---

### Case 6

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 2
Tijd 2: 60
Snelste: 60
Langzaamste: 60
Gemiddelde: 60.0
Sneller dan gemiddelde: 0
Top 3:
1: 60
2: 60
Gezochte tijd: 60
Aantal deelnemers met 200s: 0
```

**Input:**

```
2
60
60
200
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 60
Langzaamste: 60
Gemiddelde: 60.0
Sneller dan gemiddelde: 0
Top 3:
1: 60
2: 60
Aantal deelnemers met 200s: 0
```

---

### Case 7

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 1
Snelste: 200
Langzaamste: 200
Gemiddelde: 200.0
Sneller dan gemiddelde: 0
Top 3:
1: 200
Gezochte tijd: 200
Aantal deelnemers met 10s: 0
```

**Input:**

```
1
200
10
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 200
Langzaamste: 200
Gemiddelde: 200.0
Sneller dan gemiddelde: 0
Top 3:
1: 200
Aantal deelnemers met 10s: 0
```

---

### Case 8

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 3
Tijd 2: 1
Tijd 3: 1
Snelste: 1
Langzaamste: 30
Gemiddelde: 10.7
Sneller dan gemiddelde: 2
Top 3:
1: 1
2: 1
3: 30
Gezochte tijd: 30
Aantal deelnemers met 10s: 0
```

**Input:**

```
3
1
1
30
10
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 1
Langzaamste: 30
Gemiddelde: 10.7
Sneller dan gemiddelde: 2
Top 3:
1: 1
2: 1
3: 30
Aantal deelnemers met 10s: 0
```

---

### Case 9

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 1
Snelste: 60
Langzaamste: 60
Gemiddelde: 60.0
Sneller dan gemiddelde: 0
Top 3:
1: 60
Gezochte tijd: 60
Aantal deelnemers met 200s: 0
```

**Input:**

```
1
60
200
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 60
Langzaamste: 60
Gemiddelde: 60.0
Sneller dan gemiddelde: 0
Top 3:
1: 60
Aantal deelnemers met 200s: 0
```

---

### Case 10

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 2
Tijd 2: 200
Snelste: 200
Langzaamste: 200
Gemiddelde: 200.0
Sneller dan gemiddelde: 0
Top 3:
1: 200
2: 200
Gezochte tijd: 200
Aantal deelnemers met 200s: 2
```

**Input:**

```
2
200
200
200
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 200
Langzaamste: 200
Gemiddelde: 200.0
Sneller dan gemiddelde: 0
Top 3:
1: 200
2: 200
Aantal deelnemers met 200s: 2
```

---

### Case 11

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 1
Snelste: 1
Langzaamste: 1
Gemiddelde: 1.0
Sneller dan gemiddelde: 0
Top 3:
1: 1
Gezochte tijd: 1
Aantal deelnemers met 10s: 0
```

**Input:**

```
1
1
10
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 1
Langzaamste: 1
Gemiddelde: 1.0
Sneller dan gemiddelde: 0
Top 3:
1: 1
Aantal deelnemers met 10s: 0
```

---

### Case 12

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 5
Tijd 2: 30
Tijd 3: 60
Tijd 4: 10
Tijd 5: 10
Snelste: 10
Langzaamste: 60
Gemiddelde: 28.0
Sneller dan gemiddelde: 2
Top 3:
3: 10
4: 10
1: 30
Gezochte tijd: 30
Aantal deelnemers met 60s: 1
```

**Input:**

```
5
30
60
10
10
30
60
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 10
Langzaamste: 60
Gemiddelde: 28.0
Sneller dan gemiddelde: 2
Top 3:
3: 10
4: 10
1: 30
Aantal deelnemers met 60s: 1
```

---

### Case 13

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 5
Tijd 2: 100
Tijd 3: 10
Tijd 4: 1
Tijd 5: 60
Snelste: 1
Langzaamste: 200
Gemiddelde: 74.2
Sneller dan gemiddelde: 3
Top 3:
3: 1
2: 10
4: 60
Gezochte tijd: 200
Aantal deelnemers met 200s: 1
```

**Input:**

```
5
100
10
1
60
200
200
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 1
Langzaamste: 200
Gemiddelde: 74.2
Sneller dan gemiddelde: 3
Top 3:
3: 1
2: 10
4: 60
Aantal deelnemers met 200s: 1
```

---

### Case 14

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 1
Snelste: 60
Langzaamste: 60
Gemiddelde: 60.0
Sneller dan gemiddelde: 0
Top 3:
1: 60
Gezochte tijd: 60
Aantal deelnemers met 1s: 0
```

**Input:**

```
1
60
1
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 60
Langzaamste: 60
Gemiddelde: 60.0
Sneller dan gemiddelde: 0
Top 3:
1: 60
Aantal deelnemers met 1s: 0
```

---

### Case 15

**Complete console output:**

```
Aantal deelnemers: Tijd 1: 2
Tijd 2: 100
Snelste: 60
Langzaamste: 100
Gemiddelde: 80.0
Sneller dan gemiddelde: 1
Top 3:
2: 60
1: 100
Gezochte tijd: 60
Aantal deelnemers met 999s: 0
```

**Input:**

```
2
100
60
999
```

**Expected Output:**

```
Aantal deelnemers: Snelste: 60
Langzaamste: 100
Gemiddelde: 80.0
Sneller dan gemiddelde: 1
Top 3:
2: 60
1: 100
Aantal deelnemers met 999s: 0
```

---
