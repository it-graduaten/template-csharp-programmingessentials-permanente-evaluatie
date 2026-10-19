# 08_06

Maak een programma dat de gebruiker om een woord vraagt en bepaalt hoeveel klinkers het woord bevat. De klinkers zijn a, e, i, o, u (hoofd- en kleine letters tellen mee).

Het programma moet een methode bevatten die een string als parameter ontvangt en het aantal klinkers in die string teruggeeft.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Voer een woord in: huis
Aantal klinkers: 2
```

**Input:**

```
huis
```

**Expected Output:**

```
Aantal klinkers: 2
```

---

### Case 2

**Complete console output:**

```
Voer een woord in: boom
Aantal klinkers: 2
```

**Input:**

```
boom
```

**Expected Output:**

```
Aantal klinkers: 2
```

---

### Case 3

**Complete console output:**

```
Voer een woord in: aeiou
Aantal klinkers: 5
```

**Input:**

```
aeiou
```

**Expected Output:**

```
Aantal klinkers: 5
```

---

### Case 4

**Complete console output:**

```
Voer een woord in: brrrt
Aantal klinkers: 0
```

**Input:**

```
brrrt
```

**Expected Output:**

```
Aantal klinkers: 0
```

---

### Case 5

**Complete console output:**

```
Voer een woord in: AeiOu
Aantal klinkers: 5
```

**Input:**

```
AeiOu
```

**Expected Output:**

```
Aantal klinkers: 5
```
