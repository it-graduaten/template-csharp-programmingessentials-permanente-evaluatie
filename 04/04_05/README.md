# 04_05

Een restaurant wil de bestellingen van zijn klanten bijhouden. Er zijn precies drie klanten die bestellen. Het restaurant heeft drie gerechten op het menu: pasta, pizza en burger.

Tonen na alle bestellingen: hoeveel van elk gerecht er besteld is, en een overzicht van wie wat besteld heeft.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Naam van klant 1: Koen
Gerecht van klant 1: burger
Naam van klant 2: Oliver
Gerecht van klant 2: pizza
Naam van klant 3: Fien
Gerecht van klant 3: pasta
Aantal pasta: 1
Aantal pizza: 1
Aantal burger: 1
Koen - burger besteld.
Oliver - pizza besteld.
Fien - pasta besteld.
```

**Input:**

```
Koen
burger
Oliver
pizza
Fien
pasta
```

**Expected Output:**

```
Aantal pasta: 1
Aantal pizza: 1
Aantal burger: 1
Koen - burger besteld.
Oliver - pizza besteld.
Fien - pasta besteld.
```

---

### Case 2

**Complete console output:**

```
Naam van klant 1: Martin
Gerecht van klant 1: burger
Naam van klant 2: Martine
Gerecht van klant 2: pasta
Naam van klant 3: Ben
Gerecht van klant 3: burger
Aantal pasta: 1
Aantal pizza: 0
Aantal burger: 2
Martin - burger besteld.
Martine - pasta besteld.
Ben - burger besteld.
```

**Input:**

```
Martin
burger
Martine
pasta
Ben
burger
```

**Expected Output:**

```
Aantal pasta: 1
Aantal pizza: 0
Aantal burger: 2
Martin - burger besteld.
Martine - pasta besteld.
Ben - burger besteld.
```

---

### Case 3

**Complete console output:**

```
Naam van klant 1: Lea
Gerecht van klant 1: pizza
Naam van klant 2: Helena
Gerecht van klant 2: pizza
Naam van klant 3: Bruno
Gerecht van klant 3: burger
Aantal pasta: 0
Aantal pizza: 2
Aantal burger: 1
Lea - pizza besteld.
Helena - pizza besteld.
Bruno - burger besteld.
```

**Input:**

```
Lea
pizza
Helena
pizza
Bruno
burger
```

**Expected Output:**

```
Aantal pasta: 0
Aantal pizza: 2
Aantal burger: 1
Lea - pizza besteld.
Helena - pizza besteld.
Bruno - burger besteld.
```

---

### Case 4

**Complete console output:**

```
Naam van klant 1: Ann
Gerecht van klant 1: pizza
Naam van klant 2: Samuel
Gerecht van klant 2: burger
Naam van klant 3: Johan
Gerecht van klant 3: pizza
Aantal pasta: 0
Aantal pizza: 2
Aantal burger: 1
Ann - pizza besteld.
Samuel - burger besteld.
Johan - pizza besteld.
```

**Input:**

```
Ann
pizza
Samuel
burger
Johan
pizza
```

**Expected Output:**

```
Aantal pasta: 0
Aantal pizza: 2
Aantal burger: 1
Ann - pizza besteld.
Samuel - burger besteld.
Johan - pizza besteld.
```

---

### Case 5

**Complete console output:**

```
Naam van klant 1: Sonia
Gerecht van klant 1: pasta
Naam van klant 2: Tatiana
Gerecht van klant 2: pasta
Naam van klant 3: Anne
Gerecht van klant 3: burger
Aantal pasta: 2
Aantal pizza: 0
Aantal burger: 1
Sonia - pasta besteld.
Tatiana - pasta besteld.
Anne - burger besteld.
```

**Input:**

```
Sonia
pasta
Tatiana
pasta
Anne
burger
```

**Expected Output:**

```
Aantal pasta: 2
Aantal pizza: 0
Aantal burger: 1
Sonia - pasta besteld.
Tatiana - pasta besteld.
Anne - burger besteld.
```

---

### Case 6

**Complete console output:**

```
Naam van klant 1: Wendy
Gerecht van klant 1: burger
Naam van klant 2: Karima
Gerecht van klant 2: pizza
Naam van klant 3: Martina
Gerecht van klant 3: pasta
Aantal pasta: 1
Aantal pizza: 1
Aantal burger: 1
Wendy - burger besteld.
Karima - pizza besteld.
Martina - pasta besteld.
```

**Input:**

```
Wendy
burger
Karima
pizza
Martina
pasta
```

**Expected Output:**

```
Aantal pasta: 1
Aantal pizza: 1
Aantal burger: 1
Wendy - burger besteld.
Karima - pizza besteld.
Martina - pasta besteld.
```

---

### Case 7

**Complete console output:**

```
Naam van klant 1: Noah
Gerecht van klant 1: burger
Naam van klant 2: Eline
Gerecht van klant 2: pasta
Naam van klant 3: Paul
Gerecht van klant 3: pizza
Aantal pasta: 1
Aantal pizza: 1
Aantal burger: 1
Noah - burger besteld.
Eline - pasta besteld.
Paul - pizza besteld.
```

**Input:**

```
Noah
burger
Eline
pasta
Paul
pizza
```

**Expected Output:**

```
Aantal pasta: 1
Aantal pizza: 1
Aantal burger: 1
Noah - burger besteld.
Eline - pasta besteld.
Paul - pizza besteld.
```

---

### Case 8

**Complete console output:**

```
Naam van klant 1: Wesley
Gerecht van klant 1: pizza
Naam van klant 2: Eva
Gerecht van klant 2: pizza
Naam van klant 3: Dominique
Gerecht van klant 3: pasta
Aantal pasta: 1
Aantal pizza: 2
Aantal burger: 0
Wesley - pizza besteld.
Eva - pizza besteld.
Dominique - pasta besteld.
```

**Input:**

```
Wesley
pizza
Eva
pizza
Dominique
pasta
```

**Expected Output:**

```
Aantal pasta: 1
Aantal pizza: 2
Aantal burger: 0
Wesley - pizza besteld.
Eva - pizza besteld.
Dominique - pasta besteld.
```

---

### Case 9

**Complete console output:**

```
Naam van klant 1: Maria
Gerecht van klant 1: burger
Naam van klant 2: Kristof
Gerecht van klant 2: burger
Naam van klant 3: Kaat
Gerecht van klant 3: burger
Aantal pasta: 0
Aantal pizza: 0
Aantal burger: 3
Maria - burger besteld.
Kristof - burger besteld.
Kaat - burger besteld.
```

**Input:**

```
Maria
burger
Kristof
burger
Kaat
burger
```

**Expected Output:**

```
Aantal pasta: 0
Aantal pizza: 0
Aantal burger: 3
Maria - burger besteld.
Kristof - burger besteld.
Kaat - burger besteld.
```

---

### Case 10

**Complete console output:**

```
Naam van klant 1: Viviane
Gerecht van klant 1: burger
Naam van klant 2: Marc
Gerecht van klant 2: pasta
Naam van klant 3: Robin
Gerecht van klant 3: burger
Aantal pasta: 1
Aantal pizza: 0
Aantal burger: 2
Viviane - burger besteld.
Marc - pasta besteld.
Robin - burger besteld.
```

**Input:**

```
Viviane
burger
Marc
pasta
Robin
burger
```

**Expected Output:**

```
Aantal pasta: 1
Aantal pizza: 0
Aantal burger: 2
Viviane - burger besteld.
Marc - pasta besteld.
Robin - burger besteld.
```

---

### Case 11

**Complete console output:**

```
Naam van klant 1: Tuur
Gerecht van klant 1: burger
Naam van klant 2: Gino
Gerecht van klant 2: pizza
Naam van klant 3: Carine
Gerecht van klant 3: pizza
Aantal pasta: 0
Aantal pizza: 2
Aantal burger: 1
Tuur - burger besteld.
Gino - pizza besteld.
Carine - pizza besteld.
```

**Input:**

```
Tuur
burger
Gino
pizza
Carine
pizza
```

**Expected Output:**

```
Aantal pasta: 0
Aantal pizza: 2
Aantal burger: 1
Tuur - burger besteld.
Gino - pizza besteld.
Carine - pizza besteld.
```

---

### Case 12

**Complete console output:**

```
Naam van klant 1: Hendrik
Gerecht van klant 1: burger
Naam van klant 2: Dorien
Gerecht van klant 2: pasta
Naam van klant 3: Frieda
Gerecht van klant 3: pizza
Aantal pasta: 1
Aantal pizza: 1
Aantal burger: 1
Hendrik - burger besteld.
Dorien - pasta besteld.
Frieda - pizza besteld.
```

**Input:**

```
Hendrik
burger
Dorien
pasta
Frieda
pizza
```

**Expected Output:**

```
Aantal pasta: 1
Aantal pizza: 1
Aantal burger: 1
Hendrik - burger besteld.
Dorien - pasta besteld.
Frieda - pizza besteld.
```

---

### Case 13

**Complete console output:**

```
Naam van klant 1: Hendrik
Gerecht van klant 1: pasta
Naam van klant 2: Luc
Gerecht van klant 2: pasta
Naam van klant 3: Bram
Gerecht van klant 3: burger
Aantal pasta: 2
Aantal pizza: 0
Aantal burger: 1
Hendrik - pasta besteld.
Luc - pasta besteld.
Bram - burger besteld.
```

**Input:**

```
Hendrik
pasta
Luc
pasta
Bram
burger
```

**Expected Output:**

```
Aantal pasta: 2
Aantal pizza: 0
Aantal burger: 1
Hendrik - pasta besteld.
Luc - pasta besteld.
Bram - burger besteld.
```

---

### Case 14

**Complete console output:**

```
Naam van klant 1: Alexandra
Gerecht van klant 1: burger
Naam van klant 2: Liesbet
Gerecht van klant 2: pizza
Naam van klant 3: Jean
Gerecht van klant 3: pasta
Aantal pasta: 1
Aantal pizza: 1
Aantal burger: 1
Alexandra - burger besteld.
Liesbet - pizza besteld.
Jean - pasta besteld.
```

**Input:**

```
Alexandra
burger
Liesbet
pizza
Jean
pasta
```

**Expected Output:**

```
Aantal pasta: 1
Aantal pizza: 1
Aantal burger: 1
Alexandra - burger besteld.
Liesbet - pizza besteld.
Jean - pasta besteld.
```

---

### Case 15

**Complete console output:**

```
Naam van klant 1: Jana
Gerecht van klant 1: pizza
Naam van klant 2: Michèle
Gerecht van klant 2: pizza
Naam van klant 3: Said
Gerecht van klant 3: burger
Aantal pasta: 0
Aantal pizza: 2
Aantal burger: 1
Jana - pizza besteld.
Michèle - pizza besteld.
Said - burger besteld.
```

**Input:**

```
Jana
pizza
Michèle
pizza
Said
burger
```

**Expected Output:**

```
Aantal pasta: 0
Aantal pizza: 2
Aantal burger: 1
Jana - pizza besteld.
Michèle - pizza besteld.
Said - burger besteld.
```

---
