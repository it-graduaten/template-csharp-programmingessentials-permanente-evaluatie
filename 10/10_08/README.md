# 10_08

Maak een programma dat de werknemers van een bedrijf verwerkt. De gebruiker voert het aantal werknemers in en daarna voor elke werknemer de naam en het salaris. Een geldig salaris is groter dan 0. Ongeldige salarissen moeten opnieuw gevraagd worden.

Na het invoeren toont het programma:
- het totaal aantal werknemers;
- het totaal loon;
- het gemiddelde salaris (afgerond op één decimaal);
- het hoogste salaris en de naam van de werknemer;
- het laagste salaris en de naam van de werknemer.

Daarna kan de gebruiker een naam ingeven. Het programma toont het salaris van die werknemer, of een bericht dat de naam niet gevonden werd.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 3
Salaris werknemer 1: Magda
Naam werknemer 2: 1
Salaris werknemer 2: Laurent
Naam werknemer 3: 1
Salaris werknemer 3: Nancy
Totaal werknemers: 3
Totaal loon: 3002
Gemiddeld salaris: 1000.7
Hoogste: 3000 (Nancy)
Laagste: 1 (Magda)
Zoek naam: 3000
Naam niet gevonden.
```

**Input:**

```
3
Magda
1
Laurent
1
Nancy
3000
Yves
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 3
Totaal loon: 3002
Gemiddeld salaris: 1000.7
Hoogste: 3000 (Nancy)
Laagste: 1 (Magda)
Naam niet gevonden.
```

---

### Case 2

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 2
Salaris werknemer 1: Jan
Naam werknemer 2: 5000
Salaris werknemer 2: Shana
Totaal werknemers: 2
Totaal loon: 5001
Gemiddeld salaris: 2500.5
Hoogste: 5000 (Jan)
Laagste: 1 (Shana)
Zoek naam: 1
Naam niet gevonden.
```

**Input:**

```
2
Jan
5000
Shana
1
Amélie
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 2
Totaal loon: 5001
Gemiddeld salaris: 2500.5
Hoogste: 5000 (Jan)
Laagste: 1 (Shana)
Naam niet gevonden.
```

---

### Case 3

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 2
Salaris werknemer 1: Freddy
Naam werknemer 2: 1000
Salaris werknemer 2: Thomas
Totaal werknemers: 2
Totaal loon: 3000
Gemiddeld salaris: 1500.0
Hoogste: 2000 (Thomas)
Laagste: 1000 (Freddy)
Zoek naam: 2000
Naam niet gevonden.
```

**Input:**

```
2
Freddy
1000
Thomas
2000
Deborah
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 2
Totaal loon: 3000
Gemiddeld salaris: 1500.0
Hoogste: 2000 (Thomas)
Laagste: 1000 (Freddy)
Naam niet gevonden.
```

---

### Case 4

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 1
Salaris werknemer 1: Khalid
Totaal werknemers: 1
Totaal loon: 1
Gemiddeld salaris: 1.0
Hoogste: 1 (Khalid)
Laagste: 1 (Khalid)
Zoek naam: 1
Naam niet gevonden.
```

**Input:**

```
1
Khalid
1
Dominique
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 1
Totaal loon: 1
Gemiddeld salaris: 1.0
Hoogste: 1 (Khalid)
Laagste: 1 (Khalid)
Naam niet gevonden.
```

---

### Case 5

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 1
Salaris werknemer 1: Jef
Totaal werknemers: 1
Totaal loon: 5000
Gemiddeld salaris: 5000.0
Hoogste: 5000 (Jef)
Laagste: 5000 (Jef)
Zoek naam: 5000
Naam niet gevonden.
```

**Input:**

```
1
Jef
5000
Mathieu
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 1
Totaal loon: 5000
Gemiddeld salaris: 5000.0
Hoogste: 5000 (Jef)
Laagste: 5000 (Jef)
Naam niet gevonden.
```

---

### Case 6

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 3
Salaris werknemer 1: Guido
Naam werknemer 2: 2000
Salaris werknemer 2: Robbe
Naam werknemer 3: 2000
Salaris werknemer 3: Kamiel
Totaal werknemers: 3
Totaal loon: 9000
Gemiddeld salaris: 3000.0
Hoogste: 5000 (Kamiel)
Laagste: 2000 (Guido)
Zoek naam: 5000
Naam niet gevonden.
```

**Input:**

```
3
Guido
2000
Robbe
2000
Kamiel
5000
Thomas
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 3
Totaal loon: 9000
Gemiddeld salaris: 3000.0
Hoogste: 5000 (Kamiel)
Laagste: 2000 (Guido)
Naam niet gevonden.
```

---

### Case 7

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 1
Salaris werknemer 1: Katrijn
Totaal werknemers: 1
Totaal loon: 3000
Gemiddeld salaris: 3000.0
Hoogste: 3000 (Katrijn)
Laagste: 3000 (Katrijn)
Zoek naam: 3000
Naam niet gevonden.
```

**Input:**

```
1
Katrijn
3000
Mohamed
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 1
Totaal loon: 3000
Gemiddeld salaris: 3000.0
Hoogste: 3000 (Katrijn)
Laagste: 3000 (Katrijn)
Naam niet gevonden.
```

---

### Case 8

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 3
Salaris werknemer 1: Claudine
Naam werknemer 2: 3000
Salaris werknemer 2: Chloé
Naam werknemer 3: 1000
Salaris werknemer 3: Joseph
Totaal werknemers: 3
Totaal loon: 14000
Gemiddeld salaris: 4666.7
Hoogste: 10000 (Joseph)
Laagste: 1000 (Chloé)
Zoek naam: 10000
Naam niet gevonden.
```

**Input:**

```
3
Claudine
3000
Chloé
1000
Joseph
10000
André
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 3
Totaal loon: 14000
Gemiddeld salaris: 4666.7
Hoogste: 10000 (Joseph)
Laagste: 1000 (Chloé)
Naam niet gevonden.
```

---

### Case 9

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 1
Salaris werknemer 1: Joris
Totaal werknemers: 1
Totaal loon: 5000
Gemiddeld salaris: 5000.0
Hoogste: 5000 (Joris)
Laagste: 5000 (Joris)
Zoek naam: 5000
Naam niet gevonden.
```

**Input:**

```
1
Joris
5000
Johan
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 1
Totaal loon: 5000
Gemiddeld salaris: 5000.0
Hoogste: 5000 (Joris)
Laagste: 5000 (Joris)
Naam niet gevonden.
```

---

### Case 10

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 2
Salaris werknemer 1: Jonathan
Naam werknemer 2: 3000
Salaris werknemer 2: Daniel
Totaal werknemers: 2
Totaal loon: 4000
Gemiddeld salaris: 2000.0
Hoogste: 3000 (Jonathan)
Laagste: 1000 (Daniel)
Zoek naam: 1000
Naam niet gevonden.
```

**Input:**

```
2
Jonathan
3000
Daniel
1000
Amber
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 2
Totaal loon: 4000
Gemiddeld salaris: 2000.0
Hoogste: 3000 (Jonathan)
Laagste: 1000 (Daniel)
Naam niet gevonden.
```

---

### Case 11

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 1
Salaris werknemer 1: Suzanne
Totaal werknemers: 1
Totaal loon: 10000
Gemiddeld salaris: 10000.0
Hoogste: 10000 (Suzanne)
Laagste: 10000 (Suzanne)
Zoek naam: 10000
Naam niet gevonden.
```

**Input:**

```
1
Suzanne
10000
André
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 1
Totaal loon: 10000
Gemiddeld salaris: 10000.0
Hoogste: 10000 (Suzanne)
Laagste: 10000 (Suzanne)
Naam niet gevonden.
```

---

### Case 12

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 1
Salaris werknemer 1: Agnes
Totaal werknemers: 1
Totaal loon: 10000
Gemiddeld salaris: 10000.0
Hoogste: 10000 (Agnes)
Laagste: 10000 (Agnes)
Zoek naam: 10000
Naam niet gevonden.
```

**Input:**

```
1
Agnes
10000
Michèle
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 1
Totaal loon: 10000
Gemiddeld salaris: 10000.0
Hoogste: 10000 (Agnes)
Laagste: 10000 (Agnes)
Naam niet gevonden.
```

---

### Case 13

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 5
Salaris werknemer 1: Luka
Naam werknemer 2: 3000
Salaris werknemer 2: Gabrielle
Naam werknemer 3: 1000
Salaris werknemer 3: Bruno
Naam werknemer 4: 5000
Salaris werknemer 4: Jacques
Naam werknemer 5: 3000
Salaris werknemer 5: Rosita
Totaal werknemers: 5
Totaal loon: 15000
Gemiddeld salaris: 3000.0
Hoogste: 5000 (Bruno)
Laagste: 1000 (Gabrielle)
Zoek naam: 3000
Naam niet gevonden.
```

**Input:**

```
5
Luka
3000
Gabrielle
1000
Bruno
5000
Jacques
3000
Rosita
3000
Adam
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 5
Totaal loon: 15000
Gemiddeld salaris: 3000.0
Hoogste: 5000 (Bruno)
Laagste: 1000 (Gabrielle)
Naam niet gevonden.
```

---

### Case 14

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 3
Salaris werknemer 1: Dave
Naam werknemer 2: 2000
Salaris werknemer 2: Iris
Naam werknemer 3: 3000
Salaris werknemer 3: Luc
Totaal werknemers: 3
Totaal loon: 7000
Gemiddeld salaris: 2333.3
Hoogste: 3000 (Iris)
Laagste: 2000 (Dave)
Zoek naam: 2000
Naam niet gevonden.
```

**Input:**

```
3
Dave
2000
Iris
3000
Luc
2000
Kenny
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 3
Totaal loon: 7000
Gemiddeld salaris: 2333.3
Hoogste: 3000 (Iris)
Laagste: 2000 (Dave)
Naam niet gevonden.
```

---

### Case 15

**Complete console output:**

```
Aantal werknemers: Naam werknemer 1: 1
Salaris werknemer 1: Roger
Totaal werknemers: 1
Totaal loon: 5000
Gemiddeld salaris: 5000.0
Hoogste: 5000 (Roger)
Laagste: 5000 (Roger)
Zoek naam: 5000
Naam niet gevonden.
```

**Input:**

```
1
Roger
5000
Guy
```

**Expected Output:**

```
Aantal werknemers: Totaal werknemers: 1
Totaal loon: 5000
Gemiddeld salaris: 5000.0
Hoogste: 5000 (Roger)
Laagste: 5000 (Roger)
Naam niet gevonden.
```

---
