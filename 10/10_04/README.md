# 10_04

Maak een programma dat een parkeergarage simuleert. Er zijn vier soorten parkeerplaatsen: kort (€2/uur), lang (€1,50/uur), gehandicapten (gratis) en laadpalen (€3/uur).
Voor elke auto die wil parkeren kiest de gebruiker het type en daarna het aantal ingeparkerde minuten. Een negatief aantal minuten betekent dat de laatste auto is ingevoerd.

Na het invoeren toont het programma:
- het totaal aantal ingeparkerde auto's;
- het totale inkomen;
- het gemiddelde parkeertijd per auto (in minuten, afgerond op één decimaal).

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
30
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
15
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
60
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
-1
Totaal auto's: 3
Totale inkomsten: 3 euro
Gemiddelde parkeertijd: 35.0 minuten
```

**Input:**

```
2
30
4
15
2
60
2
-1
```

**Expected Output:**

```
Totaal auto's: 3
Totale inkomsten: 3 euro
Gemiddelde parkeertijd: 35.0 minuten
```

---

### Case 2

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
15
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
30
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
60
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
-1
Totaal auto's: 3
Totale inkomsten: 4.5 euro
Gemiddelde parkeertijd: 35.0 minuten
```

**Input:**

```
1
15
1
30
4
60
3
-1
```

**Expected Output:**

```
Totaal auto's: 3
Totale inkomsten: 4.5 euro
Gemiddelde parkeertijd: 35.0 minuten
```

---

### Case 3

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
60
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
30
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
0
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
-1
Totaal auto's: 3
Totale inkomsten: 1.5 euro
Gemiddelde parkeertijd: 30.0 minuten
```

**Input:**

```
3
60
4
30
1
0
1
-1
```

**Expected Output:**

```
Totaal auto's: 3
Totale inkomsten: 1.5 euro
Gemiddelde parkeertijd: 30.0 minuten
```

---

### Case 4

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
0
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
15
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
-1
Totaal auto's: 2
Totale inkomsten: 0.375 euro
Gemiddelde parkeertijd: 7.5 minuten
```

**Input:**

```
3
0
2
15
4
-1
```

**Expected Output:**

```
Totaal auto's: 2
Totale inkomsten: 0.375 euro
Gemiddelde parkeertijd: 7.5 minuten
```

---

### Case 5

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
15
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
15
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
15
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
-1
Totaal auto's: 3
Totale inkomsten: 1.625 euro
Gemiddelde parkeertijd: 15.0 minuten
```

**Input:**

```
2
15
1
15
4
15
1
-1
```

**Expected Output:**

```
Totaal auto's: 3
Totale inkomsten: 1.625 euro
Gemiddelde parkeertijd: 15.0 minuten
```

---

### Case 6

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
30
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
60
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
60
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
60
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
30
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
-1
Totaal auto's: 5
Totale inkomsten: 6.75 euro
Gemiddelde parkeertijd: 48.0 minuten
```

**Input:**

```
4
30
3
60
2
60
4
60
2
30
1
-1
```

**Expected Output:**

```
Totaal auto's: 5
Totale inkomsten: 6.75 euro
Gemiddelde parkeertijd: 48.0 minuten
```

---

### Case 7

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
15
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
30
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
0
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
30
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
-1
Totaal auto's: 4
Totale inkomsten: 0 euro
Gemiddelde parkeertijd: 18.8 minuten
```

**Input:**

```
3
15
3
30
1
0
3
30
1
-1
```

**Expected Output:**

```
Totaal auto's: 4
Totale inkomsten: 0 euro
Gemiddelde parkeertijd: 18.8 minuten
```

---

### Case 8

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
0
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
-1
Totaal auto's: 1
Totale inkomsten: 0 euro
Gemiddelde parkeertijd: 0.0 minuten
```

**Input:**

```
2
0
4
-1
```

**Expected Output:**

```
Totaal auto's: 1
Totale inkomsten: 0 euro
Gemiddelde parkeertijd: 0.0 minuten
```

---

### Case 9

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
0
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
30
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
15
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
60
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
-1
Totaal auto's: 4
Totale inkomsten: 3 euro
Gemiddelde parkeertijd: 26.2 minuten
```

**Input:**

```
2
0
4
30
3
15
2
60
2
-1
```

**Expected Output:**

```
Totaal auto's: 4
Totale inkomsten: 3 euro
Gemiddelde parkeertijd: 26.2 minuten
```

---

### Case 10

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
0
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
-1
Totaal auto's: 1
Totale inkomsten: 0 euro
Gemiddelde parkeertijd: 0.0 minuten
```

**Input:**

```
4
0
4
-1
```

**Expected Output:**

```
Totaal auto's: 1
Totale inkomsten: 0 euro
Gemiddelde parkeertijd: 0.0 minuten
```

---

### Case 11

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
0
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
60
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
30
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
30
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
30
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
-1
Totaal auto's: 5
Totale inkomsten: 3 euro
Gemiddelde parkeertijd: 30.0 minuten
```

**Input:**

```
3
0
1
60
1
30
3
30
3
30
1
-1
```

**Expected Output:**

```
Totaal auto's: 5
Totale inkomsten: 3 euro
Gemiddelde parkeertijd: 30.0 minuten
```

---

### Case 12

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
30
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
-1
Totaal auto's: 1
Totale inkomsten: 1.5 euro
Gemiddelde parkeertijd: 30.0 minuten
```

**Input:**

```
4
30
4
-1
```

**Expected Output:**

```
Totaal auto's: 1
Totale inkomsten: 1.5 euro
Gemiddelde parkeertijd: 30.0 minuten
```

---

### Case 13

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
15
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
60
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
-1
Totaal auto's: 2
Totale inkomsten: 2.25 euro
Gemiddelde parkeertijd: 37.5 minuten
```

**Input:**

```
4
15
2
60
1
-1
```

**Expected Output:**

```
Totaal auto's: 2
Totale inkomsten: 2.25 euro
Gemiddelde parkeertijd: 37.5 minuten
```

---

### Case 14

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
60
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
60
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
30
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
4
Aantal minuten: 
15
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
-1
Totaal auto's: 4
Totale inkomsten: 3.75 euro
Gemiddelde parkeertijd: 41.2 minuten
```

**Input:**

```
2
60
2
60
3
30
4
15
3
-1
```

**Expected Output:**

```
Totaal auto's: 4
Totale inkomsten: 3.75 euro
Gemiddelde parkeertijd: 41.2 minuten
```

---

### Case 15

**Complete console output:**

```
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
1
Aantal minuten: 
15
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
3
Aantal minuten: 
0
Type (1=kort, 2=lang, 3=gehandicapten, 4=laadpaal): 
2
Aantal minuten: 
-1
Totaal auto's: 2
Totale inkomsten: 0.5 euro
Gemiddelde parkeertijd: 7.5 minuten
```

**Input:**

```
1
15
3
0
2
-1
```

**Expected Output:**

```
Totaal auto's: 2
Totale inkomsten: 0.5 euro
Gemiddelde parkeertijd: 7.5 minuten
```

---
