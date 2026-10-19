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

**Description:** Run 1: args=1, 1, 4

**Input:**

```
1
1
4
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Het huidige saldo is 1000 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Het huidige saldo is 1000 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Bedankt en tot ziens!
```

---

### Case 2

**Description:** Run 2: args=3, 434, 3, 888, 3, 234, 2, 644, 3, 54, 1, 4

**Input:**

```
3
434
3
888
3
234
2
644
3
54
1
4
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je storten? Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je storten? Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je storten? Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je opnemen? Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je storten? Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Het huidige saldo is 1966 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Bedankt en tot ziens!
```

---

### Case 3

**Description:** Run 3: args=3, 960, 3, 855, 2, 1011, 1, 2, 30, 2, 518, 2, 540, 4

**Input:**

```
3
960
3
855
2
1011
1
2
30
2
518
2
540
4
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je storten? Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je storten? Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je opnemen? Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Het huidige saldo is 1804 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je opnemen? Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je opnemen? Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je opnemen? Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Bedankt en tot ziens!
```

---

### Case 4

**Description:** Run 4: args=2, 1227, 1, 4

**Input:**

```
2
1227
1
4
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je opnemen? Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Het huidige saldo is 1000 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Bedankt en tot ziens!
```

---

### Case 5

**Description:** Run 5: args=1, 3, 195, 2, 35, 2, 275, 3, 75, 2, 1306, 4

**Input:**

```
1
3
195
2
35
2
275
3
75
2
1306
4
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Het huidige saldo is 1000 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je storten? Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je opnemen? Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je opnemen? Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je storten? Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Hoeveel geld wil je opnemen? Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: Bedankt en tot ziens!
```
