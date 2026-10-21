# 08_10

Maak een programma dat een bioscoop ticketpricssysteem simuleert. De regels zijn:

- Jonger dan 12 jaar: 8 euro
- Van 12 tot en met 64 jaar: 12 euro
- Vanaf 65 jaar: 9 euro

Het programma vraagt eerst hoeveel bezoekers er zijn, waarna de gebruiker voor elke bezoeker de leeftijd invoert. Het programma berekent de totale prijs en toont hoeveel kinderen, volwassenen en senioren tickets gekocht hebben.

Het programma moet de volgende methodes bevatten:

- Een methode die de leeftijd als parameter ontvangt en de ticketprijs teruggeeft
- Een methode die de leeftijd als parameter ontvangt en de categorie teruggeeft ("Kind", "Volwassene" of "Senior")
- Een void methode die de resultaten afdrukt (ontvangst het aantal kinderen, volwassenen, senioren en de totale prijs als parameters)

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel bezoekers zijn er? 4
Leeftijd van bezoeker 1: 65
Leeftijd van bezoeker 2: 12
Leeftijd van bezoeker 3: 100
Leeftijd van bezoeker 4: 5
Kinderen: 1
Volwassenen: 1
Senioren: 2
Totale prijs: 38
```

**Input:**

```
4
65
12
100
5
```

**Expected Output:**

```
Kinderen: 1
Volwassenen: 1
Senioren: 2
Totale prijs: 38
```

---

### Case 2

**Complete console output:**

```
Hoeveel bezoekers zijn er? 3
Leeftijd van bezoeker 1: 35
Leeftijd van bezoeker 2: 11
Leeftijd van bezoeker 3: 65
Kinderen: 1
Volwassenen: 1
Senioren: 1
Totale prijs: 29
```

**Input:**

```
3
35
11
65
```

**Expected Output:**

```
Kinderen: 1
Volwassenen: 1
Senioren: 1
Totale prijs: 29
```

---

### Case 3

**Complete console output:**

```
Hoeveel bezoekers zijn er? 2
Leeftijd van bezoeker 1: 5
Leeftijd van bezoeker 2: 65
Kinderen: 1
Volwassenen: 0
Senioren: 1
Totale prijs: 17
```

**Input:**

```
2
5
65
```

**Expected Output:**

```
Kinderen: 1
Volwassenen: 0
Senioren: 1
Totale prijs: 17
```

---

### Case 4

**Complete console output:**

```
Hoeveel bezoekers zijn er? 3
Leeftijd van bezoeker 1: 100
Leeftijd van bezoeker 2: 70
Leeftijd van bezoeker 3: 0
Kinderen: 1
Volwassenen: 0
Senioren: 2
Totale prijs: 26
```

**Input:**

```
3
100
70
0
```

**Expected Output:**

```
Kinderen: 1
Volwassenen: 0
Senioren: 2
Totale prijs: 26
```

---

### Case 5

**Complete console output:**

```
Hoeveel bezoekers zijn er? 3
Leeftijd van bezoeker 1: 35
Leeftijd van bezoeker 2: 12
Leeftijd van bezoeker 3: 64
Kinderen: 0
Volwassenen: 3
Senioren: 0
Totale prijs: 36
```

**Input:**

```
3
35
12
64
```

**Expected Output:**

```
Kinderen: 0
Volwassenen: 3
Senioren: 0
Totale prijs: 36
```

---

### Case 6

**Complete console output:**

```
Hoeveel bezoekers zijn er? 3
Leeftijd van bezoeker 1: 64
Leeftijd van bezoeker 2: 5
Leeftijd van bezoeker 3: 12
Kinderen: 1
Volwassenen: 2
Senioren: 0
Totale prijs: 32
```

**Input:**

```
3
64
5
12
```

**Expected Output:**

```
Kinderen: 1
Volwassenen: 2
Senioren: 0
Totale prijs: 32
```

---

### Case 7

**Complete console output:**

```
Hoeveel bezoekers zijn er? 2
Leeftijd van bezoeker 1: 11
Leeftijd van bezoeker 2: 70
Kinderen: 1
Volwassenen: 0
Senioren: 1
Totale prijs: 17
```

**Input:**

```
2
11
70
```

**Expected Output:**

```
Kinderen: 1
Volwassenen: 0
Senioren: 1
Totale prijs: 17
```

---

### Case 8

**Complete console output:**

```
Hoeveel bezoekers zijn er? 4
Leeftijd van bezoeker 1: 12
Leeftijd van bezoeker 2: 35
Leeftijd van bezoeker 3: 5
Leeftijd van bezoeker 4: 64
Kinderen: 1
Volwassenen: 3
Senioren: 0
Totale prijs: 44
```

**Input:**

```
4
12
35
5
64
```

**Expected Output:**

```
Kinderen: 1
Volwassenen: 3
Senioren: 0
Totale prijs: 44
```

---

### Case 9

**Complete console output:**

```
Hoeveel bezoekers zijn er? 1
Leeftijd van bezoeker 1: 0
Kinderen: 1
Volwassenen: 0
Senioren: 0
Totale prijs: 8
```

**Input:**

```
1
0
```

**Expected Output:**

```
Kinderen: 1
Volwassenen: 0
Senioren: 0
Totale prijs: 8
```

---

### Case 10

**Complete console output:**

```
Hoeveel bezoekers zijn er? 3
Leeftijd van bezoeker 1: 11
Leeftijd van bezoeker 2: 0
Leeftijd van bezoeker 3: 11
Kinderen: 3
Volwassenen: 0
Senioren: 0
Totale prijs: 24
```

**Input:**

```
3
11
0
11
```

**Expected Output:**

```
Kinderen: 3
Volwassenen: 0
Senioren: 0
Totale prijs: 24
```

---

### Case 11

**Complete console output:**

```
Hoeveel bezoekers zijn er? 3
Leeftijd van bezoeker 1: 35
Leeftijd van bezoeker 2: 64
Leeftijd van bezoeker 3: 12
Kinderen: 0
Volwassenen: 3
Senioren: 0
Totale prijs: 36
```

**Input:**

```
3
35
64
12
```

**Expected Output:**

```
Kinderen: 0
Volwassenen: 3
Senioren: 0
Totale prijs: 36
```

---

### Case 12

**Complete console output:**

```
Hoeveel bezoekers zijn er? 4
Leeftijd van bezoeker 1: 12
Leeftijd van bezoeker 2: 100
Leeftijd van bezoeker 3: 5
Leeftijd van bezoeker 4: 0
Kinderen: 2
Volwassenen: 1
Senioren: 1
Totale prijs: 37
```

**Input:**

```
4
12
100
5
0
```

**Expected Output:**

```
Kinderen: 2
Volwassenen: 1
Senioren: 1
Totale prijs: 37
```

---

### Case 13

**Complete console output:**

```
Hoeveel bezoekers zijn er? 2
Leeftijd van bezoeker 1: 11
Leeftijd van bezoeker 2: 0
Kinderen: 2
Volwassenen: 0
Senioren: 0
Totale prijs: 16
```

**Input:**

```
2
11
0
```

**Expected Output:**

```
Kinderen: 2
Volwassenen: 0
Senioren: 0
Totale prijs: 16
```

---

### Case 14

**Complete console output:**

```
Hoeveel bezoekers zijn er? 4
Leeftijd van bezoeker 1: 0
Leeftijd van bezoeker 2: 35
Leeftijd van bezoeker 3: 70
Leeftijd van bezoeker 4: 11
Kinderen: 2
Volwassenen: 1
Senioren: 1
Totale prijs: 37
```

**Input:**

```
4
0
35
70
11
```

**Expected Output:**

```
Kinderen: 2
Volwassenen: 1
Senioren: 1
Totale prijs: 37
```

---

### Case 15

**Complete console output:**

```
Hoeveel bezoekers zijn er? 4
Leeftijd van bezoeker 1: 0
Leeftijd van bezoeker 2: 12
Leeftijd van bezoeker 3: 0
Leeftijd van bezoeker 4: 64
Kinderen: 2
Volwassenen: 2
Senioren: 0
Totale prijs: 40
```

**Input:**

```
4
0
12
0
64
```

**Expected Output:**

```
Kinderen: 2
Volwassenen: 2
Senioren: 0
Totale prijs: 40
```

---
