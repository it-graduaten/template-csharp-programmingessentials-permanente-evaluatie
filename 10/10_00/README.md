# 10_00

Maak een programma dat de temperatuurmetingen van een dag verwerkt. De gebruiker voert het aantal metingen in en daarna de temperatuur voor elke meting. Een geldige temperatuur ligt tussen -30 en 50 graden Celsius. Ongeldige waarden moeten opnieuw gevraagd worden.

Na het invoeren toont het programma:
- het aantal geldige metingen;
- de hoogste temperatuur;
- de laagste temperatuur;
- het gemiddelde van alle geldige temperaturen (afgerond op één decimaal).

Daarna kan de gebruiker een specifieke temperatuur ingeven. Het programma toont hoeveel metingen exact die temperatuur hebben opgeleverd.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
1
Aantal metingen: 1
Hoogste: 0
Laagste: 0
Gemiddelde: 0.0
Gezochte temperatuur: 
0
Aantal metingen met -15°C: 0
```

**Input:**

```
1
0
-15
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 1
Hoogste: 0
Laagste: 0
Gemiddelde: 0.0
Aantal metingen met -15°C: 0
```

---

### Case 2

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
3
Meting 2: 
25
Meting 3: 
20
Aantal metingen: 3
Hoogste: 25
Laagste: 10
Gemiddelde: 18.3
Gezochte temperatuur: 
10
Aantal metingen met 0°C: 0
```

**Input:**

```
3
25
20
10
0
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 3
Hoogste: 25
Laagste: 10
Gemiddelde: 18.3
Aantal metingen met 0°C: 0
```

---

### Case 3

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
1
Aantal metingen: 1
Hoogste: 0
Laagste: 0
Gemiddelde: 0.0
Gezochte temperatuur: 
0
Aantal metingen met 50°C: 0
```

**Input:**

```
1
0
50
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 1
Hoogste: 0
Laagste: 0
Gemiddelde: 0.0
Aantal metingen met 50°C: 0
```

---

### Case 4

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
3
Meting 2: 
25
Meting 3: 
25
Aantal metingen: 3
Hoogste: 25
Laagste: 0
Gemiddelde: 16.7
Gezochte temperatuur: 
0
Aantal metingen met 15°C: 0
```

**Input:**

```
3
25
25
0
15
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 3
Hoogste: 25
Laagste: 0
Gemiddelde: 16.7
Aantal metingen met 15°C: 0
```

---

### Case 5

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
2
Meting 2: 
10
Aantal metingen: 2
Hoogste: 20
Laagste: 10
Gemiddelde: 15.0
Gezochte temperatuur: 
20
Aantal metingen met 20°C: 1
```

**Input:**

```
2
10
20
20
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 2
Hoogste: 20
Laagste: 10
Gemiddelde: 15.0
Aantal metingen met 20°C: 1
```

---

### Case 6

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
5
Meting 2: 
15
Meting 3: 
-15
Meting 4: 
10
Meting 5: 
-15
Aantal metingen: 5
Hoogste: 15
Laagste: -30
Gemiddelde: -7.0
Gezochte temperatuur: 
-30
Aantal metingen met 20°C: 0
```

**Input:**

```
5
15
-15
10
-15
-30
20
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 5
Hoogste: 15
Laagste: -30
Gemiddelde: -7.0
Aantal metingen met 20°C: 0
```

---

### Case 7

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
5
Meting 2: 
-15
Meting 3: 
15
Meting 4: 
10
Meting 5: 
10
Aantal metingen: 5
Hoogste: 15
Laagste: -15
Gemiddelde: 6.0
Gezochte temperatuur: 
10
Aantal metingen met 25°C: 0
```

**Input:**

```
5
-15
15
10
10
10
25
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 5
Hoogste: 15
Laagste: -15
Gemiddelde: 6.0
Aantal metingen met 25°C: 0
```

---

### Case 8

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
3
Meting 2: 
-15
Meting 3: 
10
Aantal metingen: 3
Hoogste: 10
Laagste: -15
Gemiddelde: -6.7
Gezochte temperatuur: 
-15
Aantal metingen met 25°C: 0
```

**Input:**

```
3
-15
10
-15
25
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 3
Hoogste: 10
Laagste: -15
Gemiddelde: -6.7
Aantal metingen met 25°C: 0
```

---

### Case 9

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
1
Aantal metingen: 1
Hoogste: 0
Laagste: 0
Gemiddelde: 0.0
Gezochte temperatuur: 
0
Aantal metingen met 15°C: 0
```

**Input:**

```
1
0
15
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 1
Hoogste: 0
Laagste: 0
Gemiddelde: 0.0
Aantal metingen met 15°C: 0
```

---

### Case 10

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
3
Meting 2: 
50
Meting 3: 
15
Aantal metingen: 3
Hoogste: 50
Laagste: 15
Gemiddelde: 28.3
Gezochte temperatuur: 
20
Aantal metingen met 15°C: 1
```

**Input:**

```
3
50
15
20
15
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 3
Hoogste: 50
Laagste: 15
Gemiddelde: 28.3
Aantal metingen met 15°C: 1
```

---

### Case 11

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
5
Meting 2: 
-15
Meting 3: 
15
Meting 4: 
0
Meting 5: 
25
Aantal metingen: 5
Hoogste: 25
Laagste: -30
Gemiddelde: -1.0
Gezochte temperatuur: 
-30
Aantal metingen met 20°C: 0
```

**Input:**

```
5
-15
15
0
25
-30
20
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 5
Hoogste: 25
Laagste: -30
Gemiddelde: -1.0
Aantal metingen met 20°C: 0
```

---

### Case 12

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
5
Meting 2: 
25
Meting 3: 
15
Meting 4: 
-30
Meting 5: 
50
Aantal metingen: 5
Hoogste: 50
Laagste: -30
Gemiddelde: 9.0
Gezochte temperatuur: 
-15
Aantal metingen met -30°C: 1
```

**Input:**

```
5
25
15
-30
50
-15
-30
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 5
Hoogste: 50
Laagste: -30
Gemiddelde: 9.0
Aantal metingen met -30°C: 1
```

---

### Case 13

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
3
Meting 2: 
20
Meting 3: 
50
Aantal metingen: 3
Hoogste: 50
Laagste: 10
Gemiddelde: 26.7
Gezochte temperatuur: 
10
Aantal metingen met 15°C: 0
```

**Input:**

```
3
20
50
10
15
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 3
Hoogste: 50
Laagste: 10
Gemiddelde: 26.7
Aantal metingen met 15°C: 0
```

---

### Case 14

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
3
Meting 2: 
-15
Meting 3: 
-30
Aantal metingen: 3
Hoogste: 0
Laagste: -30
Gemiddelde: -15.0
Gezochte temperatuur: 
0
Aantal metingen met 50°C: 0
```

**Input:**

```
3
-15
-30
0
50
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 3
Hoogste: 0
Laagste: -30
Gemiddelde: -15.0
Aantal metingen met 50°C: 0
```

---

### Case 15

**Complete console output:**

```
Aantal metingen: 
Meting 1: 
3
Meting 2: 
-30
Meting 3: 
10
Aantal metingen: 3
Hoogste: 10
Laagste: -30
Gemiddelde: -3.3
Gezochte temperatuur: 
10
Aantal metingen met 0°C: 0
```

**Input:**

```
3
-30
10
10
0
```

**Expected Output:**

```
Aantal metingen:
Aantal metingen: 3
Hoogste: 10
Laagste: -30
Gemiddelde: -3.3
Aantal metingen met 0°C: 0
```

---
