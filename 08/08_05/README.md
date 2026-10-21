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
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 2
Hoeveel geld wil je opnemen? 1000
Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 4
Bedankt en tot ziens!
```

**Input:**

```
2
1000
4
2
500
1
3
100
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Bedankt en tot ziens!
```

---

### Case 2

**Complete console output:**

```
NONZERO_EXIT(134): Unhandled exception. System.ArgumentNullException: Value cannot be null. (Parameter 's')
   at System.Int32.Parse(String s)
   at Program.ToonMenu() in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 41
   at Program.Main(String[] args) in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 50
```

**Input:**

```
1
2
0
3
1000
1
2
1000
```

**Expected Output:**

```
NONZERO_EXIT(134): Unhandled exception. System.ArgumentNullException: Value cannot be null. (Parameter 's')
   at System.Int32.Parse(String s)
   at Program.ToonMenu() in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 41
   at Program.Main(String[] args) in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 50
```

---

### Case 3

**Complete console output:**

```
NONZERO_EXIT(134): Unhandled exception. System.ArgumentNullException: Value cannot be null. (Parameter 's')
   at System.Int32.Parse(String s)
   at Program.ToonMenu() in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 41
   at Program.Main(String[] args) in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 50
```

**Input:**

```
1
3
100
1
1
3
1000
```

**Expected Output:**

```
NONZERO_EXIT(134): Unhandled exception. System.ArgumentNullException: Value cannot be null. (Parameter 's')
   at System.Int32.Parse(String s)
   at Program.ToonMenu() in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 41
   at Program.Main(String[] args) in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 50
```

---

### Case 4

**Complete console output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 1
Het huidige saldo is 1000 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 2
Hoeveel geld wil je opnemen? 1500
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 4
Bedankt en tot ziens!
```

**Input:**

```
1
2
1500
4
2
500
3
100
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Het huidige saldo is 1000 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Bedankt en tot ziens!
```

---

### Case 5

**Complete console output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 3
Hoeveel geld wil je storten? 500
Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 2
Hoeveel geld wil je opnemen? 1000
Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 4
Bedankt en tot ziens!
```

**Input:**

```
3
500
2
1000
4
2
1000
3
100
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Bedankt en tot ziens!
```

---

### Case 6

**Complete console output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 4
Bedankt en tot ziens!
```

**Input:**

```
4
3
100
1
2
0
1
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Bedankt en tot ziens!
```

---

### Case 7

**Complete console output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 3
Hoeveel geld wil je storten? 0
Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 2
Hoeveel geld wil je opnemen? 1000
Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 2
Hoeveel geld wil je opnemen? 0
Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 3
Hoeveel geld wil je storten? 1000
Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 4
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
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Bedankt en tot ziens!
```

---

### Case 8

**Complete console output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 4
Bedankt en tot ziens!
```

**Input:**

```
4
4
1
1
3
100
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Bedankt en tot ziens!
```

---

### Case 9

**Complete console output:**

```
NONZERO_EXIT(134): Unhandled exception. System.ArgumentNullException: Value cannot be null. (Parameter 's')
   at System.Int32.Parse(String s)
   at Program.ToonMenu() in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 41
   at Program.Main(String[] args) in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 50
```

**Input:**

```
2
0
2
1500
2
500
1
1
```

**Expected Output:**

```
NONZERO_EXIT(134): Unhandled exception. System.ArgumentNullException: Value cannot be null. (Parameter 's')
   at System.Int32.Parse(String s)
   at Program.ToonMenu() in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 41
   at Program.Main(String[] args) in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 50
```

---

### Case 10

**Complete console output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 2
Hoeveel geld wil je opnemen? 0
Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 4
Bedankt en tot ziens!
```

**Input:**

```
2
0
4
3
500
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
Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Bedankt en tot ziens!
```

---

### Case 11

**Complete console output:**

```
NONZERO_EXIT(134): Unhandled exception. System.ArgumentNullException: Value cannot be null. (Parameter 's')
   at System.Int32.Parse(String s)
   at Program.ToonMenu() in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 41
   at Program.Main(String[] args) in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 50
```

**Input:**

```
3
0
1
1
2
1000
3
100
```

**Expected Output:**

```
NONZERO_EXIT(134): Unhandled exception. System.ArgumentNullException: Value cannot be null. (Parameter 's')
   at System.Int32.Parse(String s)
   at Program.ToonMenu() in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 41
   at Program.Main(String[] args) in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 50
```

---

### Case 12

**Complete console output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 3
Hoeveel geld wil je storten? 100
Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 2
Hoeveel geld wil je opnemen? 1500
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 4
Bedankt en tot ziens!
```

**Input:**

```
3
100
2
1500
4
3
1000
2
1000
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Storting succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Bedankt en tot ziens!
```

---

### Case 13

**Complete console output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 1
Het huidige saldo is 1000 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 2
Hoeveel geld wil je opnemen? 1500
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 1
Het huidige saldo is 1000 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 2
Hoeveel geld wil je opnemen? 0
Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 4
Bedankt en tot ziens!
```

**Input:**

```
1
2
1500
1
2
0
4
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Het huidige saldo is 1000 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kan niet meer opnemen dan er op de rekening staat.
Onvoldoende saldo.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Het huidige saldo is 1000 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Opname succesvol.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Bedankt en tot ziens!
```

---

### Case 14

**Complete console output:**

```
NONZERO_EXIT(134): Unhandled exception. System.ArgumentNullException: Value cannot be null. (Parameter 's')
   at System.Int32.Parse(String s)
   at Program.ToonMenu() in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 41
   at Program.Main(String[] args) in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 50
```

**Input:**

```
1
1
1
2
1500
2
0
```

**Expected Output:**

```
NONZERO_EXIT(134): Unhandled exception. System.ArgumentNullException: Value cannot be null. (Parameter 's')
   at System.Int32.Parse(String s)
   at Program.ToonMenu() in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 41
   at Program.Main(String[] args) in /workspace/exercise-solutions/programming-essentials/08/08_05/consoleapp/Program.cs:line 50
```

---

### Case 15

**Complete console output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 1
Het huidige saldo is 1000 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Kies een optie: 4
Bedankt en tot ziens!
```

**Input:**

```
1
4
1
1
1
```

**Expected Output:**

```
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Het huidige saldo is 1000 euro.
--- Bankautomaat ---
1. Saldo bekijken
2. Geld opnemen
3. Geld storten
4. Stoppen
Bedankt en tot ziens!
```

---
