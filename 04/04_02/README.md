# 04_02

Een gebruiker wil een boodschappenlijst bijhouden. Gebruik een List<string> om de items te bewaren.

Vraag de gebruiker om vijf producten in te voeren. Voeg elk product toe aan de lijst.

Vraag daarna of de gebruiker een product wil verwijderen. Als ja, vraag dan welk product. Verwijder het product uit de lijst.

Tonen: het aantal producten na het verwijderen.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Geef product 1: melk
Geef product 2: croissants
Geef product 3: kaas
Geef product 4: bananen
Geef product 5: koekjes
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
melk
croissants
kaas
bananen
koekjes
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 2

**Complete console output:**

```
Geef product 1: fruitsap
Geef product 2: pistolets
Geef product 3: kaas
Geef product 4: bananen
Geef product 5: chips
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
fruitsap
pistolets
kaas
bananen
chips
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 3

**Complete console output:**

```
Geef product 1: fruitsap
Geef product 2: croissants
Geef product 3: kipfilet
Geef product 4: peren
Geef product 5: chocolade
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
fruitsap
croissants
kipfilet
peren
chocolade
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 4

**Complete console output:**

```
Geef product 1: fruitsap
Geef product 2: pistolets
Geef product 3: ham
Geef product 4: bananen
Geef product 5: koekjes
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
fruitsap
pistolets
ham
bananen
koekjes
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 5

**Complete console output:**

```
Geef product 1: melk
Geef product 2: brood
Geef product 3: kaas
Geef product 4: peren
Geef product 5: chips
Wil je een product verwijderen? (ja/nee): ja
Welk product wil je verwijderen? fruitsap
Aantal producten: 5
```

**Input:**

```
melk
brood
kaas
peren
chips
ja
fruitsap
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 6

**Complete console output:**

```
Geef product 1: melk
Geef product 2: croissants
Geef product 3: kaas
Geef product 4: peren
Geef product 5: chocolade
Wil je een product verwijderen? (ja/nee): ja
Welk product wil je verwijderen? water
Aantal producten: 5
```

**Input:**

```
melk
croissants
kaas
peren
chocolade
ja
water
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 7

**Complete console output:**

```
Geef product 1: fruitsap
Geef product 2: croissants
Geef product 3: ham
Geef product 4: peren
Geef product 5: chocolade
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
fruitsap
croissants
ham
peren
chocolade
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 8

**Complete console output:**

```
Geef product 1: fruitsap
Geef product 2: pistolets
Geef product 3: kaas
Geef product 4: bananen
Geef product 5: chocolade
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
fruitsap
pistolets
kaas
bananen
chocolade
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 9

**Complete console output:**

```
Geef product 1: water
Geef product 2: brood
Geef product 3: ham
Geef product 4: bananen
Geef product 5: chips
Wil je een product verwijderen? (ja/nee): ja
Welk product wil je verwijderen? brood
Aantal producten: 4
```

**Input:**

```
water
brood
ham
bananen
chips
ja
brood
```

**Expected Output:**

```
Aantal producten: 4
```

---

### Case 10

**Complete console output:**

```
Geef product 1: melk
Geef product 2: brood
Geef product 3: kipfilet
Geef product 4: bananen
Geef product 5: koekjes
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
melk
brood
kipfilet
bananen
koekjes
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 11

**Complete console output:**

```
Geef product 1: water
Geef product 2: croissants
Geef product 3: ham
Geef product 4: bananen
Geef product 5: koekjes
Wil je een product verwijderen? (ja/nee): ja
Welk product wil je verwijderen? peren
Aantal producten: 5
```

**Input:**

```
water
croissants
ham
bananen
koekjes
ja
peren
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 12

**Complete console output:**

```
Geef product 1: melk
Geef product 2: croissants
Geef product 3: ham
Geef product 4: appels
Geef product 5: chocolade
Wil je een product verwijderen? (ja/nee): ja
Welk product wil je verwijderen? chocolade
Aantal producten: 4
```

**Input:**

```
melk
croissants
ham
appels
chocolade
ja
chocolade
```

**Expected Output:**

```
Aantal producten: 4
```

---

### Case 13

**Complete console output:**

```
Geef product 1: fruitsap
Geef product 2: croissants
Geef product 3: kipfilet
Geef product 4: peren
Geef product 5: chocolade
Wil je een product verwijderen? (ja/nee): ja
Welk product wil je verwijderen? chocolade
Aantal producten: 4
```

**Input:**

```
fruitsap
croissants
kipfilet
peren
chocolade
ja
chocolade
```

**Expected Output:**

```
Aantal producten: 4
```

---

### Case 14

**Complete console output:**

```
Geef product 1: water
Geef product 2: pistolets
Geef product 3: kipfilet
Geef product 4: bananen
Geef product 5: chocolade
Wil je een product verwijderen? (ja/nee): ja
Welk product wil je verwijderen? bananen
Aantal producten: 4
```

**Input:**

```
water
pistolets
kipfilet
bananen
chocolade
ja
bananen
```

**Expected Output:**

```
Aantal producten: 4
```

---

### Case 15

**Complete console output:**

```
Geef product 1: water
Geef product 2: pistolets
Geef product 3: kaas
Geef product 4: peren
Geef product 5: chocolade
Wil je een product verwijderen? (ja/nee): ja
Welk product wil je verwijderen? appels
Aantal producten: 5
```

**Input:**

```
water
pistolets
kaas
peren
chocolade
ja
appels
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 16

**Complete console output:**

```
Geef product 1: water
Geef product 2: pistolets
Geef product 3: kipfilet
Geef product 4: appels
Geef product 5: koekjes
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
water
pistolets
kipfilet
appels
koekjes
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 17

**Complete console output:**

```
Geef product 1: melk
Geef product 2: brood
Geef product 3: kaas
Geef product 4: bananen
Geef product 5: koekjes
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
melk
brood
kaas
bananen
koekjes
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 18

**Complete console output:**

```
Geef product 1: water
Geef product 2: brood
Geef product 3: kipfilet
Geef product 4: bananen
Geef product 5: chocolade
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
water
brood
kipfilet
bananen
chocolade
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 19

**Complete console output:**

```
Geef product 1: melk
Geef product 2: pistolets
Geef product 3: kipfilet
Geef product 4: peren
Geef product 5: koekjes
Wil je een product verwijderen? (ja/nee): ja
Welk product wil je verwijderen? brood
Aantal producten: 5
```

**Input:**

```
melk
pistolets
kipfilet
peren
koekjes
ja
brood
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 20

**Complete console output:**

```
Geef product 1: water
Geef product 2: croissants
Geef product 3: kipfilet
Geef product 4: bananen
Geef product 5: koekjes
Wil je een product verwijderen? (ja/nee): ja
Welk product wil je verwijderen? croissants
Aantal producten: 4
```

**Input:**

```
water
croissants
kipfilet
bananen
koekjes
ja
croissants
```

**Expected Output:**

```
Aantal producten: 4
```

---

### Case 21

**Complete console output:**

```
Geef product 1: water
Geef product 2: brood
Geef product 3: kaas
Geef product 4: appels
Geef product 5: chocolade
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
water
brood
kaas
appels
chocolade
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 22

**Complete console output:**

```
Geef product 1: fruitsap
Geef product 2: pistolets
Geef product 3: kaas
Geef product 4: bananen
Geef product 5: chips
Wil je een product verwijderen? (ja/nee): ja
Welk product wil je verwijderen? croissants
Aantal producten: 5
```

**Input:**

```
fruitsap
pistolets
kaas
bananen
chips
ja
croissants
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 23

**Complete console output:**

```
Geef product 1: water
Geef product 2: brood
Geef product 3: kipfilet
Geef product 4: appels
Geef product 5: chocolade
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
water
brood
kipfilet
appels
chocolade
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 24

**Complete console output:**

```
Geef product 1: fruitsap
Geef product 2: pistolets
Geef product 3: kipfilet
Geef product 4: bananen
Geef product 5: chocolade
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
fruitsap
pistolets
kipfilet
bananen
chocolade
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---

### Case 25

**Complete console output:**

```
Geef product 1: water
Geef product 2: croissants
Geef product 3: ham
Geef product 4: peren
Geef product 5: chips
Wil je een product verwijderen? (ja/nee): nee
Aantal producten: 5
```

**Input:**

```
water
croissants
ham
peren
chips
nee
```

**Expected Output:**

```
Aantal producten: 5
```

---
