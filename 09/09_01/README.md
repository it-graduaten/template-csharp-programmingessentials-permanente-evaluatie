# 09_01

Je krijgt de volgende code te zien:

```csharp
int score = int.Parse(Console.ReadLine());

if (score >= 10)
{
    Console.WriteLine("Geslaagd");
}
else if (score >= 16)
{
    Console.WriteLine("Uitstekend");
}
```

Vraag de gebruiker om een score in en voer de bovenstaande code uit met die invoer.

Wat is het probleem met deze code? Een score van 18 zou "Uitstekend" moeten tonen, maar dat gebeurt niet.

Pas de code aan zodat deze correct werkt.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Voer een score in: 18
Uitstekend
```

**Input:**

```
18
```

**Expected Output:**

```
Uitstekend
```

---

### Case 2

**Complete console output:**

```
Voer een score in: 15
Geslaagd
```

**Input:**

```
15
```

**Expected Output:**

```
Geslaagd
```

---

### Case 3

**Complete console output:**

```
Voer een score in: 10
Geslaagd
```

**Input:**

```
10
```

**Expected Output:**

```
Geslaagd
```

---

### Case 4

**Complete console output:**

```
Voer een score in: 20
Uitstekend
```

**Input:**

```
20
```

**Expected Output:**

```
Uitstekend
```

---

### Case 5

**Complete console output:**

```
Voer een score in: 5
Geslaagd
```

**Input:**

```
5
```

**Expected Output:**

```
Geslaagd
```
