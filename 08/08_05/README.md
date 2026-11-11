# 08_05

Maak een programma dat een eenvoudige bankautomaat simuleert. De gebruiker start met een beginstand van 1000 euro.

Het programma moet de volgende methodes bevatten:

- Een methode die het saldo teruggeeft (ontvangt het huidige saldo als parameter en geeft het terug)
- Een methode die geld opneemt (ontvangt het huidige saldo en het opnemen bedrag als parameters, geeft het nieuwe saldo terug; kan niet meer opnemen dan er op de rekening staat)
- Een methode die geld stort (ontvangt het huidige saldo en het stortingsbedrag als parameters, geeft het nieuwe saldo terug)
- Een void methode die het huidige saldo afdrukt (ontvangt het saldo als parameter)
- Een methode die het menu toont en de keuze van de gebruiker teruggeeft (geen parameters nodig)

De gebruiker kiest: saldo bekijken, geld opnemen, geld storten, of stoppen. Het saldo moet altijd positief blijven (niet negatief worden na opname).

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 1000 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
0
Opname succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
3
Hoeveel geld wil je storten? 
1000
Storting succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 2000 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
1
2
0
3
1000
1
4
```

**Expected Output:**

```
Het huidige saldo is 1000 euro.
Opname succesvol.
Storting succesvol.
Het huidige saldo is 2000 euro.
Bedankt en tot ziens!
```

---

### Case 2

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 1000 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 1000 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
3
Hoeveel geld wil je storten? 
100
Storting succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 1100 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
500
Opname succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
3
Hoeveel geld wil je storten? 
500
Storting succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
3
Hoeveel geld wil je storten? 
1000
Storting succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 2100 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
1
1
3
100
1
2
500
3
500
3
1000
1
4
2
500
4
```

**Expected Output:**

```
Het huidige saldo is 1000 euro.
Het huidige saldo is 1000 euro.
Storting succesvol.
Het huidige saldo is 1100 euro.
Opname succesvol.
Storting succesvol.
Storting succesvol.
Het huidige saldo is 2100 euro.
Bedankt en tot ziens!
```

---

### Case 3

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
0
Opname succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
1500
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
3
Hoeveel geld wil je storten? 
1000
Storting succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
3
Hoeveel geld wil je storten? 
1000
Storting succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
2
0
2
1500
3
1000
3
1000
4
2
1500
2
500
1
4
4
```

**Expected Output:**

```
Opname succesvol.
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
Storting succesvol.
Storting succesvol.
Bedankt en tot ziens!
```

---

### Case 4

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 1000 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
1500
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 1000 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
1500
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
500
Opname succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
1
2
1500
1
2
1500
2
500
4
```

**Expected Output:**

```
Het huidige saldo is 1000 euro.
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
Het huidige saldo is 1000 euro.
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
Opname succesvol.
Bedankt en tot ziens!
```

---

### Case 5

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 1000 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 1000 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
1000
Opname succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
1
1
2
1000
4
2
0
4
4
```

**Expected Output:**

```
Het huidige saldo is 1000 euro.
Het huidige saldo is 1000 euro.
Opname succesvol.
Bedankt en tot ziens!
```

---

### Case 6

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
500
Opname succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 500 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
2
500
1
4
```

**Expected Output:**

```
Opname succesvol.
Het huidige saldo is 500 euro.
Bedankt en tot ziens!
```

---

### Case 7

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
1000
Opname succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
2
1000
4
4
1
2
500
3
1000
1
4
```

**Expected Output:**

```
Opname succesvol.
Bedankt en tot ziens!
```

---

### Case 8

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
4
3
100
4
```

**Expected Output:**

```
Bedankt en tot ziens!
```

---

### Case 9

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
1500
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
3
Hoeveel geld wil je storten? 
1000
Storting succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
2
1500
3
1000
4
3
500
3
0
2
1000
4
4
```

**Expected Output:**

```
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
Storting succesvol.
Bedankt en tot ziens!
```

---

### Case 10

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
0
Opname succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 1000 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
2
0
1
4
4
3
100
4
1
2
1000
2
0
4
```

**Expected Output:**

```
Opname succesvol.
Het huidige saldo is 1000 euro.
Bedankt en tot ziens!
```

---

### Case 11

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
4
4
```

**Expected Output:**

```
Bedankt en tot ziens!
```

---

### Case 12

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
4
3
500
3
1000
2
1500
1
2
1000
4
4
```

**Expected Output:**

```
Bedankt en tot ziens!
```

---

### Case 13

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 1000 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 1000 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
1
Het huidige saldo is 1000 euro.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
1
1
1
4
1
2
0
4
```

**Expected Output:**

```
Het huidige saldo is 1000 euro.
Het huidige saldo is 1000 euro.
Het huidige saldo is 1000 euro.
Bedankt en tot ziens!
```

---

### Case 14

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
3
Hoeveel geld wil je storten? 
0
Storting succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
1000
Opname succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
2
Hoeveel geld wil je opnemen? 
0
Opname succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
3
Hoeveel geld wil je storten? 
1000
Storting succesvol.
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
3
0
2
1000
2
0
3
1000
4
3
1000
1
2
1500
4
```

**Expected Output:**

```
Storting succesvol.
Opname succesvol.
Opname succesvol.
Storting succesvol.
Bedankt en tot ziens!
```

---

### Case 15

**Complete console output:**

```
Kies een optie:
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Maak een keuze: 
4
Bedankt en tot ziens!
```

**Input:**

```
4
3
1000
4
```

**Expected Output:**

```
Bedankt en tot ziens!
```

---
