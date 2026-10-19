# 08_03

Maak een programma dat de gebruiker om een aantal dagen vraagt en vervolgens voor elke dag de temperatuur in graden Celsius invoert. Het programma berekent en toont het gemiddelde, de hoogste en de laagste temperatuur.

Het programma moet de volgende methodes bevatten:

- Een methode die de hoogste temperatuur teruggeeft van een array met temperaturen ( ontvangt de array als parameter)
- Een methode die de laagste temperatuur teruggeeft van een array met temperaturen (ontvangst de array als parameter)
- Een methode die het gemiddelde van een array met temperaturen teruggeeft als double (ontvangst de array als parameter)

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 3
Temperatuur dag 1: 10
Temperatuur dag 2: 15
Temperatuur dag 3: 20
Gemiddelde: 15
Hoogste: 20
Laagste: 10
```

**Input:**

```
3
10
15
20
```

**Expected Output:**

```
Gemiddelde: 15
Hoogste: 20
Laagste: 10
```

---

### Case 2

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 5
Temperatuur dag 1: -5
Temperatuur dag 2: 3
Temperatuur dag 3: 8
Temperatuur dag 4: -2
Temperatuur dag 5: 12
Gemiddelde: 2
Hoogste: 12
Laagste: -5
```

**Input:**

```
5
-5
3
8
-2
12
```

**Expected Output:**

```
Gemiddelde: 2
Hoogste: 12
Laagste: -5
```

---

### Case 3

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 1
Temperatuur dag 1: 25
Gemiddelde: 25
Hoogste: 25
Laagste: 25
```

**Input:**

```
1
25
```

**Expected Output:**

```
Gemiddelde: 25
Hoogste: 25
Laagste: 25
```

---

### Case 4

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 4
Temperatuur dag 1: 0
Temperatuur dag 2: 0
Temperatuur dag 3: 0
Temperatuur dag 4: 0
Gemiddelde: 0
Hoogste: 0
Laagste: 0
```

**Input:**

```
4
0
0
0
0
```

**Expected Output:**

```
Gemiddelde: 0
Hoogste: 0
Laagste: 0
```

---

### Case 5

**Complete console output:**

```
Hoeveel dagen wil je invoeren? 3
Temperatuur dag 1: -10
Temperatuur dag 2: -10
Temperatuur dag 3: -10
Gemiddelde: -10
Hoogste: -10
Laagste: -10
```

**Input:**

```
3
-10
-10
-10
```

**Expected Output:**

```
Gemiddelde: -10
Hoogste: -10
Laagste: -10
```
