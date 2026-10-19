# 09_00

Je krijgt de volgende code te zien:

```csharp
int leeftijd = 18;

if (leeftijd > 18)
{
    Console.WriteLine("Volwassen");
}
else
{
    Console.WriteLine("Minderjarig");
}
```

Vraag de gebruiker om een leeftijd in en voer de bovenstaande code uit met die invoer.

Wat is het probleem met deze code als iemand vanaf 18 jaar volwassen beschouwd moet worden?

Pas de code aan zodat deze correct werkt.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Voer je leeftijd in: 17
Minderjarig
```

**Input:**

```
17
```

**Expected Output:**

```
Minderjarig
```

---

### Case 2

**Complete console output:**

```
Voer je leeftijd in: 18
Volwassen
```

**Input:**

```
18
```

**Expected Output:**

```
Volwassen
```

---

### Case 3

**Complete console output:**

```
Voer je leeftijd in: 20
Volwassen
```

**Input:**

```
20
```

**Expected Output:**

```
Volwassen
```

---

### Case 4

**Complete console output:**

```
Voer je leeftijd in: 65
Volwassen
```

**Input:**

```
65
```

**Expected Output:**

```
Volwassen
```

---

### Case 5

**Complete console output:**

```
Voer je leeftijd in: 10
Minderjarig
```

**Input:**

```
10
```

**Expected Output:**

```
Minderjarig
```
