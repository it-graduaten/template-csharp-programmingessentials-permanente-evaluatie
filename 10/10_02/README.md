# 10_02

Maak een programma dat een productcatalogus beheert. De gebruiker kan producten toevoegen met een naam en een prijs. De prijs moet positief zijn. De gebruiker kan ook stoppen met toevoegen door een lege naam in te voeren.

Na het toevoegen van alle producten toont het programma:
- het aantal producten;
- de totale waarde van alle producten;
- het gemiddelde productprijs;
- het duurste product.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Productnaam: boek3
Prijs: 50
Productnaam: boek4
Prijs: 1
Productnaam: boek6
Prijs: 50
Productnaam: 
Aantal producten: 3
Totale waarde: 101
Gemiddelde prijs: 33.7
Duurst: boek3 (50)
```

**Input:**

```
boek3
50
boek4
1
boek6
50


```

**Expected Output:**

```
Aantal producten: 3
Totale waarde: 101
Gemiddelde prijs: 33.7
Duurst: boek3 (50)
```

---

### Case 2

**Complete console output:**

```
Productnaam: boek2
Prijs: 25
Productnaam: boek5
Prijs: 1
Productnaam: 
Aantal producten: 2
Totale waarde: 26
Gemiddelde prijs: 13.0
Duurst: boek2 (25)
```

**Input:**

```
boek2
25
boek5
1


boek8
50
```

**Expected Output:**

```
Aantal producten: 2
Totale waarde: 26
Gemiddelde prijs: 13.0
Duurst: boek2 (25)
```

---

### Case 3

**Complete console output:**

```
Productnaam: boek1
Prijs: 15
Productnaam: boek5
Prijs: 10
Productnaam: boek6
Prijs: 25
Productnaam: boek7
Prijs: 50
Productnaam: 
Aantal producten: 4
Totale waarde: 100
Gemiddelde prijs: 25.0
Duurst: boek7 (50)
```

**Input:**

```
boek1
15
boek5
10
boek6
25
boek7
50

```

**Expected Output:**

```
Aantal producten: 4
Totale waarde: 100
Gemiddelde prijs: 25.0
Duurst: boek7 (50)
```

---

### Case 4

**Complete console output:**

```
Productnaam: boek1
Prijs: 10
Productnaam: boek5
Prijs: 10
Productnaam: boek6
Prijs: 15
Productnaam: 
Aantal producten: 3
Totale waarde: 35
Gemiddelde prijs: 11.7
Duurst: boek6 (15)
```

**Input:**

```
boek1
10
boek5
10
boek6
15

boek8
15
```

**Expected Output:**

```
Aantal producten: 3
Totale waarde: 35
Gemiddelde prijs: 11.7
Duurst: boek6 (15)
```

---

### Case 5

**Complete console output:**

```
Productnaam: 
Geen producten ingevoerd.
```

**Input:**

```

boek4
1

boek7
25

```

**Expected Output:**

```
Geen producten ingevoerd.
```

---

### Case 6

**Complete console output:**

```
Productnaam: 
Geen producten ingevoerd.
```

**Input:**

```

boek5
15
boek6
10
boek7
50
boek8
1
```

**Expected Output:**

```
Geen producten ingevoerd.
```

---

### Case 7

**Complete console output:**

```
Productnaam: boek3
Prijs: 25
Productnaam: 
Aantal producten: 1
Totale waarde: 25
Gemiddelde prijs: 25.0
Duurst: boek3 (25)
```

**Input:**

```
boek3
25

boek6
50
boek7
25

```

**Expected Output:**

```
Aantal producten: 1
Totale waarde: 25
Gemiddelde prijs: 25.0
Duurst: boek3 (25)
```

---

### Case 8

**Complete console output:**

```
Productnaam: boek1
Prijs: 1
Productnaam: 
Aantal producten: 1
Totale waarde: 1
Gemiddelde prijs: 1.0
Duurst: boek1 (1)
```

**Input:**

```
boek1
1




```

**Expected Output:**

```
Aantal producten: 1
Totale waarde: 1
Gemiddelde prijs: 1.0
Duurst: boek1 (1)
```

---

### Case 9

**Complete console output:**

```
Productnaam: 
Geen producten ingevoerd.
```

**Input:**

```

boek5
25

boek7
1
boek8
10
```

**Expected Output:**

```
Geen producten ingevoerd.
```

---

### Case 10

**Complete console output:**

```
Productnaam: boek1
Prijs: 25
Productnaam: boek4
Prijs: 50
Productnaam: boek6
Prijs: 25
Productnaam: boek7
Prijs: 25
Productnaam: 
Aantal producten: 4
Totale waarde: 125
Gemiddelde prijs: 31.2
Duurst: boek4 (50)
```

**Input:**

```
boek1
25
boek4
50
boek6
25
boek7
25

```

**Expected Output:**

```
Aantal producten: 4
Totale waarde: 125
Gemiddelde prijs: 31.2
Duurst: boek4 (50)
```

---

### Case 11

**Complete console output:**

```
Productnaam: boek3
Prijs: 1
Productnaam: boek5
Prijs: 15
Productnaam: 
Aantal producten: 2
Totale waarde: 16
Gemiddelde prijs: 8.0
Duurst: boek5 (15)
```

**Input:**

```
boek3
1
boek5
15



```

**Expected Output:**

```
Aantal producten: 2
Totale waarde: 16
Gemiddelde prijs: 8.0
Duurst: boek5 (15)
```

---

### Case 12

**Complete console output:**

```
Productnaam: 
Geen producten ingevoerd.
```

**Input:**

```

boek5
10

boek7
15
boek8
15
```

**Expected Output:**

```
Geen producten ingevoerd.
```

---

### Case 13

**Complete console output:**

```
Productnaam: boek3
Prijs: 15
Productnaam: 
Aantal producten: 1
Totale waarde: 15
Gemiddelde prijs: 15.0
Duurst: boek3 (15)
```

**Input:**

```
boek3
15

boek6
15

boek8
15
```

**Expected Output:**

```
Aantal producten: 1
Totale waarde: 15
Gemiddelde prijs: 15.0
Duurst: boek3 (15)
```

---

### Case 14

**Complete console output:**

```
Productnaam: 
Geen producten ingevoerd.
```

**Input:**

```



boek7
25

```

**Expected Output:**

```
Geen producten ingevoerd.
```

---

### Case 15

**Complete console output:**

```
Productnaam: boek2
Prijs: 25
Productnaam: boek5
Prijs: 50
Productnaam: boek6
Prijs: 15
Productnaam: 
Aantal producten: 3
Totale waarde: 90
Gemiddelde prijs: 30.0
Duurst: boek5 (50)
```

**Input:**

```
boek2
25
boek5
50
boek6
15


```

**Expected Output:**

```
Aantal producten: 3
Totale waarde: 90
Gemiddelde prijs: 30.0
Duurst: boek5 (50)
```

---
