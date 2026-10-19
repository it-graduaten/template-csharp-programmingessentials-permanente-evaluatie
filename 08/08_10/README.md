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
Hoeveel bezoekers zijn er? 3
Leeftijd van bezoeker 1: 8
Leeftijd van bezoeker 2: 35
Leeftijd van bezoeker 3: 70
Kinderen: 1
Volwassenen: 1
Senioren: 1
Totale prijs: 29
```

**Input:**

```
3
8
35
70
```

**Expected Output:**

```
Kinderen: 1
Volwassenen: 1
Senioren: 1
Totale prijs: 29
```

---

### Case 2

**Complete console output:**

```
Hoeveel bezoekers zijn er? 2
Leeftijd van bezoeker 1: 11
Leeftijd van bezoeker 2: 12
Kinderen: 1
Volwassenen: 1
Senioren: 0
Totale prijs: 20
```

**Input:**

```
2
11
12
```

**Expected Output:**

```
Kinderen: 1
Volwassenen: 1
Senioren: 0
Totale prijs: 20
```

---

### Case 3

**Complete console output:**

```
Hoeveel bezoekers zijn er? 4
Leeftijd van bezoeker 1: 65
Leeftijd van bezoeker 2: 70
Leeftijd van bezoeker 3: 80
Leeftijd van bezoeker 4: 5
Kinderen: 1
Volwassenen: 0
Senioren: 3
Totale prijs: 35
```

**Input:**

```
4
65
70
80
5
```

**Expected Output:**

```
Kinderen: 1
Volwassenen: 0
Senioren: 3
Totale prijs: 35
```

---

### Case 4

**Complete console output:**

```
Hoeveel bezoekers zijn er? 1
Leeftijd van bezoeker 1: 64
Kinderen: 0
Volwassenen: 1
Senioren: 0
Totale prijs: 12
```

**Input:**

```
1
64
```

**Expected Output:**

```
Kinderen: 0
Volwassenen: 1
Senioren: 0
Totale prijs: 12
```

---

### Case 5

**Complete console output:**

```
Hoeveel bezoekers zijn er? 3
Leeftijd van bezoeker 1: 0
Leeftijd van bezoeker 2: 100
Leeftijd van bezoeker 3: 12
Kinderen: 1
Volwassenen: 1
Senioren: 1
Totale prijs: 29
```

**Input:**

```
3
0
100
12
```

**Expected Output:**

```
Kinderen: 1
Volwassenen: 1
Senioren: 1
Totale prijs: 29
```
