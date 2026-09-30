# 04_04

Een bioscoop wil de ticketverkoop voor drie verschillende filmvoorstellingen bijhouden. Er zijn precies drie voorstellingen per dag.

Vraag de gebruiker om het aantal verkochte tickets voor elke voorstelling. Sla de resultaten op in een array van het type int.

Tonen: het totale aantal verkochte tickets en welke voorstelling de meeste tickets heeft verkocht (met de voorstellingsnummer: 1, 2 of 3).

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 132
Geef aantal verkochte tickets voor voorstelling 2: 28
Geef aantal verkochte tickets voor voorstelling 3: 69
Totaal aantal verkochte tickets: 229
Voorstelling 1 heeft de meeste tickets verkocht met 132 tickets.
```

**Input:**

```
132
28
69
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 229
Voorstelling 1 heeft de meeste tickets verkocht met 132 tickets.
```

---

### Case 2

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 175
Geef aantal verkochte tickets voor voorstelling 2: 168
Geef aantal verkochte tickets voor voorstelling 3: 200
Totaal aantal verkochte tickets: 543
Voorstelling 3 heeft de meeste tickets verkocht met 200 tickets.
```

**Input:**

```
175
168
200
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 543
Voorstelling 3 heeft de meeste tickets verkocht met 200 tickets.
```

---

### Case 3

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 12
Geef aantal verkochte tickets voor voorstelling 2: 2
Geef aantal verkochte tickets voor voorstelling 3: 60
Totaal aantal verkochte tickets: 74
Voorstelling 3 heeft de meeste tickets verkocht met 60 tickets.
```

**Input:**

```
12
2
60
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 74
Voorstelling 3 heeft de meeste tickets verkocht met 60 tickets.
```

---

### Case 4

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 132
Geef aantal verkochte tickets voor voorstelling 2: 3
Geef aantal verkochte tickets voor voorstelling 3: 146
Totaal aantal verkochte tickets: 281
Voorstelling 3 heeft de meeste tickets verkocht met 146 tickets.
```

**Input:**

```
132
3
146
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 281
Voorstelling 3 heeft de meeste tickets verkocht met 146 tickets.
```

---

### Case 5

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 78
Geef aantal verkochte tickets voor voorstelling 2: 50
Geef aantal verkochte tickets voor voorstelling 3: 114
Totaal aantal verkochte tickets: 242
Voorstelling 3 heeft de meeste tickets verkocht met 114 tickets.
```

**Input:**

```
78
50
114
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 242
Voorstelling 3 heeft de meeste tickets verkocht met 114 tickets.
```

---

### Case 6

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 111
Geef aantal verkochte tickets voor voorstelling 2: 150
Geef aantal verkochte tickets voor voorstelling 3: 21
Totaal aantal verkochte tickets: 282
Voorstelling 2 heeft de meeste tickets verkocht met 150 tickets.
```

**Input:**

```
111
150
21
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 282
Voorstelling 2 heeft de meeste tickets verkocht met 150 tickets.
```

---

### Case 7

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 15
Geef aantal verkochte tickets voor voorstelling 2: 28
Geef aantal verkochte tickets voor voorstelling 3: 125
Totaal aantal verkochte tickets: 168
Voorstelling 3 heeft de meeste tickets verkocht met 125 tickets.
```

**Input:**

```
15
28
125
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 168
Voorstelling 3 heeft de meeste tickets verkocht met 125 tickets.
```

---

### Case 8

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 65
Geef aantal verkochte tickets voor voorstelling 2: 58
Geef aantal verkochte tickets voor voorstelling 3: 88
Totaal aantal verkochte tickets: 211
Voorstelling 3 heeft de meeste tickets verkocht met 88 tickets.
```

**Input:**

```
65
58
88
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 211
Voorstelling 3 heeft de meeste tickets verkocht met 88 tickets.
```

---

### Case 9

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 140
Geef aantal verkochte tickets voor voorstelling 2: 108
Geef aantal verkochte tickets voor voorstelling 3: 191
Totaal aantal verkochte tickets: 439
Voorstelling 3 heeft de meeste tickets verkocht met 191 tickets.
```

**Input:**

```
140
108
191
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 439
Voorstelling 3 heeft de meeste tickets verkocht met 191 tickets.
```

---

### Case 10

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 90
Geef aantal verkochte tickets voor voorstelling 2: 155
Geef aantal verkochte tickets voor voorstelling 3: 40
Totaal aantal verkochte tickets: 285
Voorstelling 2 heeft de meeste tickets verkocht met 155 tickets.
```

**Input:**

```
90
155
40
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 285
Voorstelling 2 heeft de meeste tickets verkocht met 155 tickets.
```

---

### Case 11

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 132
Geef aantal verkochte tickets voor voorstelling 2: 199
Geef aantal verkochte tickets voor voorstelling 3: 67
Totaal aantal verkochte tickets: 398
Voorstelling 2 heeft de meeste tickets verkocht met 199 tickets.
```

**Input:**

```
132
199
67
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 398
Voorstelling 2 heeft de meeste tickets verkocht met 199 tickets.
```

---

### Case 12

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 122
Geef aantal verkochte tickets voor voorstelling 2: 174
Geef aantal verkochte tickets voor voorstelling 3: 23
Totaal aantal verkochte tickets: 319
Voorstelling 2 heeft de meeste tickets verkocht met 174 tickets.
```

**Input:**

```
122
174
23
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 319
Voorstelling 2 heeft de meeste tickets verkocht met 174 tickets.
```

---

### Case 13

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 164
Geef aantal verkochte tickets voor voorstelling 2: 158
Geef aantal verkochte tickets voor voorstelling 3: 187
Totaal aantal verkochte tickets: 509
Voorstelling 3 heeft de meeste tickets verkocht met 187 tickets.
```

**Input:**

```
164
158
187
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 509
Voorstelling 3 heeft de meeste tickets verkocht met 187 tickets.
```

---

### Case 14

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 149
Geef aantal verkochte tickets voor voorstelling 2: 107
Geef aantal verkochte tickets voor voorstelling 3: 89
Totaal aantal verkochte tickets: 345
Voorstelling 1 heeft de meeste tickets verkocht met 149 tickets.
```

**Input:**

```
149
107
89
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 345
Voorstelling 1 heeft de meeste tickets verkocht met 149 tickets.
```

---

### Case 15

**Complete console output:**

```
Geef aantal verkochte tickets voor voorstelling 1: 99
Geef aantal verkochte tickets voor voorstelling 2: 169
Geef aantal verkochte tickets voor voorstelling 3: 37
Totaal aantal verkochte tickets: 305
Voorstelling 2 heeft de meeste tickets verkocht met 169 tickets.
```

**Input:**

```
99
169
37
```

**Expected Output:**

```
Totaal aantal verkochte tickets: 305
Voorstelling 2 heeft de meeste tickets verkocht met 169 tickets.
```

---
