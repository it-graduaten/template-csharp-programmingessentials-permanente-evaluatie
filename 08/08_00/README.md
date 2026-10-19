# 08_00

Maak een programma dat de gebruiker om het aankoopbedrag van een product vraagt en berekent hoeveel de klant moet betalen met korting. Een winkel geeft 10% korting wanneer het totale aankoopbedrag minstens 100 euro bedraagt.

Het programma moet een methode bevatten die de korting berekent op basis van het aankoopbedrag. Als het aankoopbedrag minstens 100 euro is, geeft de methode 10% korting terug als een getal. Anders geeft de methode 0 terug.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Voer het aankoopbedrag in: 50
Te betalen: 50
```

**Input:**

```
50
```

**Expected Output:**

```
Te betalen: 50
```

---

### Case 2

**Complete console output:**

```
Voer het aankoopbedrag in: 150
Korting: 15
Te betalen: 135
```

**Input:**

```
150
```

**Expected Output:**

```
Korting: 15
Te betalen: 135
```

---

### Case 3

**Complete console output:**

```
Voer het aankoopbedrag in: 100
Korting: 10
Te betalen: 90
```

**Input:**

```
100
```

**Expected Output:**

```
Korting: 10
Te betalen: 90
```

---

### Case 4

**Complete console output:**

```
Voer het aankoopbedrag in: 200
Korting: 20
Te betalen: 180
```

**Input:**

```
200
```

**Expected Output:**

```
Korting: 20
Te betalen: 180
```

---

### Case 5

**Complete console output:**

```
Voer het aankoopbedrag in: 99
Te betalen: 99
```

**Input:**

```
99
```

**Expected Output:**

```
Te betalen: 99
```
