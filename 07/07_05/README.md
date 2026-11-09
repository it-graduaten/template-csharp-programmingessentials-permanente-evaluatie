# 07_05

Maak een programma voor een adreslijst. De gebruiker kan namen toevoegen aan de lijst en de lijst weergeven.

Het programma heeft de volgende methodes nodig:

- Een void methode om een naam toe te voegen aan de lijst (met de lijst als parameter)
- Een void methode om alle namen in de lijst af te drukken (met de lijst als parameter)
- Een methode die een bool teruggeeft om te controleren of een bepaalde naam in de lijst staat (met de lijst en de gezochte naam als parameters)
- Een methode die het aantal namen in de lijst teruggeeft (met de lijst als parameter)

De gebruiker kiest een optie: (1) een naam toevoegen, (2) de lijst tonen, (3) een naam zoeken, (4) het aantal namen bekijken of (5) stoppen. Het programma stopt wanneer de gebruiker kiest om te stoppen.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de gezochte naam in: 3
De naam 'David' staat niet in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen

De namen in de lijst:
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
3
David
2
5
```

**Expected Output:**

```
De naam 'David' staat niet in de lijst.
De namen in de lijst:
```

---

### Case 2

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen

De namen in de lijst:
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de naam in: 2
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de gezochte naam in: 1
De naam 'David' staat niet in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
2
1
Charlie
3
David
5
```

**Expected Output:**

```
De namen in de lijst:
De naam 'David' staat niet in de lijst.
```

---

### Case 3

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
5
5
```

**Expected Output:**

```
```

---

### Case 4

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
5
3
Eve
5
5
```

**Expected Output:**

```
```

---

### Case 5

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Er zijn 0 namen in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen

De namen in de lijst:
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de naam in: 4
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
4
2
1
Bob
5
```

**Expected Output:**

```
Er zijn 0 namen in de lijst.
De namen in de lijst:
```

---

### Case 6

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de naam in: 1
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
1
David
5
```

**Expected Output:**

```
```

---

### Case 7

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
5
4
5
```

**Expected Output:**

```
```

---

### Case 8

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen

De namen in de lijst:
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Er zijn 0 namen in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
2
4
5
```

**Expected Output:**

```
De namen in de lijst:
Er zijn 0 namen in de lijst.
```

---

### Case 9

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de naam in: 1
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
1
Alice
5
```

**Expected Output:**

```
```

---

### Case 10

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de naam in: 1
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
1
Charlie
5
```

**Expected Output:**

```
```

---

### Case 11

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen

De namen in de lijst:
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
2
5
4
5
```

**Expected Output:**

```
De namen in de lijst:
```

---

### Case 12

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen

De namen in de lijst:
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
2
5
2
5
```

**Expected Output:**

```
De namen in de lijst:
```

---

### Case 13

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Er zijn 0 namen in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
4
5
```

**Expected Output:**

```
Er zijn 0 namen in de lijst.
```

---

### Case 14

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Er zijn 0 namen in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
4
5
```

**Expected Output:**

```
Er zijn 0 namen in de lijst.
```

---

### Case 15

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Er zijn 0 namen in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de gezochte naam in: 4
De naam 'Eve' staat niet in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
4
3
Eve
5
```

**Expected Output:**

```
Er zijn 0 namen in de lijst.
De naam 'Eve' staat niet in de lijst.
```

---

### Case 16

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen

De namen in de lijst:
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de naam in: 2
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
2
1
Eve
5
```

**Expected Output:**

```
De namen in de lijst:
```

---

### Case 17

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Er zijn 0 namen in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen

De namen in de lijst:
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
4
2
5
5
```

**Expected Output:**

```
Er zijn 0 namen in de lijst.
De namen in de lijst:
```

---

### Case 18

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de naam in: 1
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de gezochte naam in: David
De naam 'David' staat in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Er zijn 1 namen in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
1
David
3
David
4
5
```

**Expected Output:**

```
De naam 'David' staat in de lijst.
Er zijn 1 namen in de lijst.
```

---

### Case 19

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de gezochte naam in: 3
De naam 'Alice' staat niet in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen

De namen in de lijst:
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
3
Alice
2
5
5
```

**Expected Output:**

```
De naam 'Alice' staat niet in de lijst.
De namen in de lijst:
```

---

### Case 20

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Er zijn 0 namen in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de naam in: 4
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
4
1
David
5
```

**Expected Output:**

```
Er zijn 0 namen in de lijst.
```

---

### Case 21

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Er zijn 0 namen in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
4
5
```

**Expected Output:**

```
Er zijn 0 namen in de lijst.
```

---

### Case 22

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de naam in: 1
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Voer de naam in: David
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
1
David
1
Bob
5
```

**Expected Output:**

```
```

---

### Case 23

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Er zijn 0 namen in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
4
5
```

**Expected Output:**

```
Er zijn 0 namen in de lijst.
```

---

### Case 24

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
Er zijn 0 namen in de lijst.
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
4
5
2
5
```

**Expected Output:**

```
Er zijn 0 namen in de lijst.
```

---

### Case 25

**Complete console output:**

```
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen

De namen in de lijst:
Kies een optie:
1. Naam toevoegen
2. Lijst tonen
3. Naam zoeken
4. Aantal namen bekijken
5. Stoppen
```

**Input:**

```
2
5
5
```

**Expected Output:**

```
De namen in de lijst:
```

---
