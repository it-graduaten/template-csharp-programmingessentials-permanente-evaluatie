# 03_10

Schrijf een programma dat een e-mailadres valideert volgens de volgende regels:

- Het e-mailadres moet minstens 5 karakters lang zijn.
- Het e-mailadres moet een @ bevatten.
- Er moet een punt (.) na de @ staan.
- De extensie na het laatste punt moet een geldige domeinextensie zijn: .be, .nl, .com of .org.

Vraag de gebruiker om een e-mailadres en controleer het op geldigheid. Toon "Geldig e-mailadres" als alle regels voldaan zijn, of een specifieke foutmelding voor elke overtreding.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Geef een e-mail adres: test@
Ongeldig e-mailadres. Geen punt na @ gevonden.
```

**Input:**

```
test@
```

**Expected Output:**

```
Ongeldig e-mailadres. Geen punt na @ gevonden.
```

---

### Case 2

**Complete console output:**

```
Geef een e-mail adres: abc
Ongeldig e-mailadres. Te kort.
```

**Input:**

```
abc
```

**Expected Output:**

```
Ongeldig e-mailadres. Te kort.
```

---

### Case 3

**Complete console output:**

```
Geef een e-mail adres: testexample.com
Ongeldig e-mailadres. Geen @ gevonden.
```

**Input:**

```
testexample.com
```

**Expected Output:**

```
Ongeldig e-mailadres. Geen @ gevonden.
```

---

### Case 4

**Complete console output:**

```
Geef een e-mail adres: test@.be
Geldig e-mailadres
```

**Input:**

```
test@.be
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 5

**Complete console output:**

```
Geef een e-mail adres: student@school.nl
Geldig e-mailadres
```

**Input:**

```
student@school.nl
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 6

**Complete console output:**

```
Geef een e-mail adres: student@school.nl
Geldig e-mailadres
```

**Input:**

```
student@school.nl
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 7

**Complete console output:**

```
Geef een e-mail adres: test@example.com
Geldig e-mailadres
```

**Input:**

```
test@example.com
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 8

**Complete console output:**

```
Geef een e-mail adres: @test.be
Geldig e-mailadres
```

**Input:**

```
@test.be
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 9

**Complete console output:**

```
Geef een e-mail adres: test@@example.com
Geldig e-mailadres
```

**Input:**

```
test@@example.com
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 10

**Complete console output:**

```
Geef een e-mail adres: joren@thomasmore.be
Geldig e-mailadres
```

**Input:**

```
joren@thomasmore.be
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 11

**Complete console output:**

```
Geef een e-mail adres: test@example.eu
Ongeldige e-mail extensie.
```

**Input:**

```
test@example.eu
```

**Expected Output:**

```
Ongeldige e-mail extensie.
```

---

### Case 12

**Complete console output:**

```
Geef een e-mail adres: test@example.eu
Ongeldige e-mail extensie.
```

**Input:**

```
test@example.eu
```

**Expected Output:**

```
Ongeldige e-mail extensie.
```

---

### Case 13

**Complete console output:**

```
Geef een e-mail adres: test@example.eu
Ongeldige e-mail extensie.
```

**Input:**

```
test@example.eu
```

**Expected Output:**

```
Ongeldige e-mail extensie.
```

---

### Case 14

**Complete console output:**

```
Geef een e-mail adres: student@school.nl
Geldig e-mailadres
```

**Input:**

```
student@school.nl
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 15

**Complete console output:**

```
Geef een e-mail adres: test@example.com
Geldig e-mailadres
```

**Input:**

```
test@example.com
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 16

**Complete console output:**

```
Geef een e-mail adres: test@example
Ongeldig e-mailadres. Geen punt na @ gevonden.
```

**Input:**

```
test@example
```

**Expected Output:**

```
Ongeldig e-mailadres. Geen punt na @ gevonden.
```

---

### Case 17

**Complete console output:**

```
Geef een e-mail adres: x@y.nl
Geldig e-mailadres
```

**Input:**

```
x@y.nl
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 18

**Complete console output:**

```
Geef een e-mail adres: test@
Ongeldig e-mailadres. Geen punt na @ gevonden.
```

**Input:**

```
test@
```

**Expected Output:**

```
Ongeldig e-mailadres. Geen punt na @ gevonden.
```

---

### Case 19

**Complete console output:**

```
Geef een e-mail adres: test@example
Ongeldig e-mailadres. Geen punt na @ gevonden.
```

**Input:**

```
test@example
```

**Expected Output:**

```
Ongeldig e-mailadres. Geen punt na @ gevonden.
```

---

### Case 20

**Complete console output:**

```
Geef een e-mail adres: test@@example.com
Geldig e-mailadres
```

**Input:**

```
test@@example.com
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 21

**Complete console output:**

```
Geef een e-mail adres: x@y.nl
Geldig e-mailadres
```

**Input:**

```
x@y.nl
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 22

**Complete console output:**

```
Geef een e-mail adres: test@.be
Geldig e-mailadres
```

**Input:**

```
test@.be
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 23

**Complete console output:**

```
Geef een e-mail adres: test@example.eu
Ongeldige e-mail extensie.
```

**Input:**

```
test@example.eu
```

**Expected Output:**

```
Ongeldige e-mail extensie.
```

---

### Case 24

**Complete console output:**

```
Geef een e-mail adres: x@y.nl
Geldig e-mailadres
```

**Input:**

```
x@y.nl
```

**Expected Output:**

```
Geldig e-mailadres
```

---

### Case 25

**Complete console output:**

```
Geef een e-mail adres: info@organisatie.org
Geldig e-mailadres
```

**Input:**

```
info@organisatie.org
```

**Expected Output:**

```
Geldig e-mailadres
```

---
