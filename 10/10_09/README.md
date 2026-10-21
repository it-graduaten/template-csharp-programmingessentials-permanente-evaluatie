# 10_09

Maak een programma dat de scores van een examenanalyse verwerkt. De gebruiker voert het aantal studenten in en daarna voor elke student de score. Een geldige score ligt tussen 0 en 20. Ongeldige scores moeten opnieuw gevraagd worden.

Na het invoeren toont het programma:
- het gemiddelde;
- de hoogste score;
- de laagste score;
- het aantal geslaagde studenten (een score van 10 of meer is geslaagd);
- het aantal studenten per cijferklasse: 0-4, 5-7, 8-9, 10-11, 12-13, 14-15, 16-17, 18-20.

Daarna kan de gebruiker een score ingeven. Het programma toont hoeveel studenten die score hebben behaald.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Aantal studenten: Score student 1: 3
Score student 2: 0
Score student 3: 4
Gemiddelde: 4.3
Hoogste: 9
Laagste: 0
Geslaagd: 0
Cijferklassen:
0-4: 2
5-7: 0
8-9: 1
10-11: 0
12-13: 0
14-15: 0
16-17: 0
18-20: 0
Gezochte score: 9
Aantal studenten met score 11: 0
```

**Input:**

```
3
0
4
9
11
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 4.3
Hoogste: 9
Laagste: 0
Geslaagd: 0
Cijferklassen:
0-4: 2
5-7: 0
8-9: 1
10-11: 0
12-13: 0
14-15: 0
16-17: 0
18-20: 0
Aantal studenten met score 11: 0
```

---

### Case 2

**Complete console output:**

```
Aantal studenten: Score student 1: 1
Gemiddelde: 7.0
Hoogste: 7
Laagste: 7
Geslaagd: 0
Cijferklassen:
0-4: 0
5-7: 1
8-9: 0
10-11: 0
12-13: 0
14-15: 0
16-17: 0
18-20: 0
Gezochte score: 7
Aantal studenten met score 13: 0
```

**Input:**

```
1
7
13
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 7.0
Hoogste: 7
Laagste: 7
Geslaagd: 0
Cijferklassen:
0-4: 0
5-7: 1
8-9: 0
10-11: 0
12-13: 0
14-15: 0
16-17: 0
18-20: 0
Aantal studenten met score 13: 0
```

---

### Case 3

**Complete console output:**

```
Aantal studenten: Score student 1: 3
Score student 2: 13
Score student 3: 11
Gemiddelde: 11.0
Hoogste: 13
Laagste: 9
Geslaagd: 2
Cijferklassen:
0-4: 0
5-7: 0
8-9: 1
10-11: 1
12-13: 1
14-15: 0
16-17: 0
18-20: 0
Gezochte score: 9
Aantal studenten met score 17: 0
```

**Input:**

```
3
13
11
9
17
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 11.0
Hoogste: 13
Laagste: 9
Geslaagd: 2
Cijferklassen:
0-4: 0
5-7: 0
8-9: 1
10-11: 1
12-13: 1
14-15: 0
16-17: 0
18-20: 0
Aantal studenten met score 17: 0
```

---

### Case 4

**Complete console output:**

```
Aantal studenten: Score student 1: 2
Score student 2: 13
Gemiddelde: 10.0
Hoogste: 13
Laagste: 7
Geslaagd: 1
Cijferklassen:
0-4: 0
5-7: 1
8-9: 0
10-11: 0
12-13: 1
14-15: 0
16-17: 0
18-20: 0
Gezochte score: 7
Aantal studenten met score 15: 0
```

**Input:**

```
2
13
7
15
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 10.0
Hoogste: 13
Laagste: 7
Geslaagd: 1
Cijferklassen:
0-4: 0
5-7: 1
8-9: 0
10-11: 0
12-13: 1
14-15: 0
16-17: 0
18-20: 0
Aantal studenten met score 15: 0
```

---

### Case 5

**Complete console output:**

```
Aantal studenten: Score student 1: 3
Score student 2: 15
Score student 3: 15
Gemiddelde: 10.0
Hoogste: 15
Laagste: 0
Geslaagd: 2
Cijferklassen:
0-4: 1
5-7: 0
8-9: 0
10-11: 0
12-13: 0
14-15: 2
16-17: 0
18-20: 0
Gezochte score: 0
Aantal studenten met score 99: 0
```

**Input:**

```
3
15
15
0
99
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 10.0
Hoogste: 15
Laagste: 0
Geslaagd: 2
Cijferklassen:
0-4: 1
5-7: 0
8-9: 0
10-11: 0
12-13: 0
14-15: 2
16-17: 0
18-20: 0
Aantal studenten met score 99: 0
```

---

### Case 6

**Complete console output:**

```
Aantal studenten: Score student 1: 2
Score student 2: 9
Gemiddelde: 14.5
Hoogste: 20
Laagste: 9
Geslaagd: 1
Cijferklassen:
0-4: 0
5-7: 0
8-9: 1
10-11: 0
12-13: 0
14-15: 0
16-17: 0
18-20: 1
Gezochte score: 20
Aantal studenten met score 0: 0
```

**Input:**

```
2
9
20
0
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 14.5
Hoogste: 20
Laagste: 9
Geslaagd: 1
Cijferklassen:
0-4: 0
5-7: 0
8-9: 1
10-11: 0
12-13: 0
14-15: 0
16-17: 0
18-20: 1
Aantal studenten met score 0: 0
```

---

### Case 7

**Complete console output:**

```
Aantal studenten: Score student 1: 3
Score student 2: 0
Score student 3: 0
Gemiddelde: 4.3
Hoogste: 13
Laagste: 0
Geslaagd: 1
Cijferklassen:
0-4: 2
5-7: 0
8-9: 0
10-11: 0
12-13: 1
14-15: 0
16-17: 0
18-20: 0
Gezochte score: 13
Aantal studenten met score 20: 0
```

**Input:**

```
3
0
0
13
20
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 4.3
Hoogste: 13
Laagste: 0
Geslaagd: 1
Cijferklassen:
0-4: 2
5-7: 0
8-9: 0
10-11: 0
12-13: 1
14-15: 0
16-17: 0
18-20: 0
Aantal studenten met score 20: 0
```

---

### Case 8

**Complete console output:**

```
Aantal studenten: Score student 1: 1
Gemiddelde: 4.0
Hoogste: 4
Laagste: 4
Geslaagd: 0
Cijferklassen:
0-4: 1
5-7: 0
8-9: 0
10-11: 0
12-13: 0
14-15: 0
16-17: 0
18-20: 0
Gezochte score: 4
Aantal studenten met score 11: 0
```

**Input:**

```
1
4
11
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 4.0
Hoogste: 4
Laagste: 4
Geslaagd: 0
Cijferklassen:
0-4: 1
5-7: 0
8-9: 0
10-11: 0
12-13: 0
14-15: 0
16-17: 0
18-20: 0
Aantal studenten met score 11: 0
```

---

### Case 9

**Complete console output:**

```
Aantal studenten: Score student 1: 3
Score student 2: 4
Score student 3: 0
Gemiddelde: 3.7
Hoogste: 7
Laagste: 0
Geslaagd: 0
Cijferklassen:
0-4: 2
5-7: 1
8-9: 0
10-11: 0
12-13: 0
14-15: 0
16-17: 0
18-20: 0
Gezochte score: 7
Aantal studenten met score 7: 1
```

**Input:**

```
3
4
0
7
7
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 3.7
Hoogste: 7
Laagste: 0
Geslaagd: 0
Cijferklassen:
0-4: 2
5-7: 1
8-9: 0
10-11: 0
12-13: 0
14-15: 0
16-17: 0
18-20: 0
Aantal studenten met score 7: 1
```

---

### Case 10

**Complete console output:**

```
Aantal studenten: Score student 1: 5
Score student 2: 20
Score student 3: 17
Score student 4: 7
Score student 5: 15
Gemiddelde: 14.8
Hoogste: 20
Laagste: 7
Geslaagd: 4
Cijferklassen:
0-4: 0
5-7: 1
8-9: 0
10-11: 0
12-13: 0
14-15: 2
16-17: 1
18-20: 1
Gezochte score: 15
Aantal studenten met score 20: 1
```

**Input:**

```
5
20
17
7
15
15
20
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 14.8
Hoogste: 20
Laagste: 7
Geslaagd: 4
Cijferklassen:
0-4: 0
5-7: 1
8-9: 0
10-11: 0
12-13: 0
14-15: 2
16-17: 1
18-20: 1
Aantal studenten met score 20: 1
```

---

### Case 11

**Complete console output:**

```
Aantal studenten: Score student 1: 1
Gemiddelde: 13.0
Hoogste: 13
Laagste: 13
Geslaagd: 1
Cijferklassen:
0-4: 0
5-7: 0
8-9: 0
10-11: 0
12-13: 1
14-15: 0
16-17: 0
18-20: 0
Gezochte score: 13
Aantal studenten met score 15: 0
```

**Input:**

```
1
13
15
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 13.0
Hoogste: 13
Laagste: 13
Geslaagd: 1
Cijferklassen:
0-4: 0
5-7: 0
8-9: 0
10-11: 0
12-13: 1
14-15: 0
16-17: 0
18-20: 0
Aantal studenten met score 15: 0
```

---

### Case 12

**Complete console output:**

```
Aantal studenten: Score student 1: 2
Score student 2: 13
Gemiddelde: 11.0
Hoogste: 13
Laagste: 9
Geslaagd: 1
Cijferklassen:
0-4: 0
5-7: 0
8-9: 1
10-11: 0
12-13: 1
14-15: 0
16-17: 0
18-20: 0
Gezochte score: 9
Aantal studenten met score 4: 0
```

**Input:**

```
2
13
9
4
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 11.0
Hoogste: 13
Laagste: 9
Geslaagd: 1
Cijferklassen:
0-4: 0
5-7: 0
8-9: 1
10-11: 0
12-13: 1
14-15: 0
16-17: 0
18-20: 0
Aantal studenten met score 4: 0
```

---

### Case 13

**Complete console output:**

```
Aantal studenten: Score student 1: 2
Score student 2: 13
Gemiddelde: 13.0
Hoogste: 13
Laagste: 13
Geslaagd: 2
Cijferklassen:
0-4: 0
5-7: 0
8-9: 0
10-11: 0
12-13: 2
14-15: 0
16-17: 0
18-20: 0
Gezochte score: 13
Aantal studenten met score 13: 2
```

**Input:**

```
2
13
13
13
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 13.0
Hoogste: 13
Laagste: 13
Geslaagd: 2
Cijferklassen:
0-4: 0
5-7: 0
8-9: 0
10-11: 0
12-13: 2
14-15: 0
16-17: 0
18-20: 0
Aantal studenten met score 13: 2
```

---

### Case 14

**Complete console output:**

```
Aantal studenten: Score student 1: 1
Gemiddelde: 4.0
Hoogste: 4
Laagste: 4
Geslaagd: 0
Cijferklassen:
0-4: 1
5-7: 0
8-9: 0
10-11: 0
12-13: 0
14-15: 0
16-17: 0
18-20: 0
Gezochte score: 4
Aantal studenten met score 4: 1
```

**Input:**

```
1
4
4
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 4.0
Hoogste: 4
Laagste: 4
Geslaagd: 0
Cijferklassen:
0-4: 1
5-7: 0
8-9: 0
10-11: 0
12-13: 0
14-15: 0
16-17: 0
18-20: 0
Aantal studenten met score 4: 1
```

---

### Case 15

**Complete console output:**

```
Aantal studenten: Score student 1: 1
Gemiddelde: 17.0
Hoogste: 17
Laagste: 17
Geslaagd: 1
Cijferklassen:
0-4: 0
5-7: 0
8-9: 0
10-11: 0
12-13: 0
14-15: 0
16-17: 1
18-20: 0
Gezochte score: 17
Aantal studenten met score 4: 0
```

**Input:**

```
1
17
4
```

**Expected Output:**

```
Aantal studenten: Gemiddelde: 17.0
Hoogste: 17
Laagste: 17
Geslaagd: 1
Cijferklassen:
0-4: 0
5-7: 0
8-9: 0
10-11: 0
12-13: 0
14-15: 0
16-17: 1
18-20: 0
Aantal studenten met score 4: 0
```

---
