# 09_08

Je krijgt de volgende code te zien:

```csharp
Console.WriteLine("Geef een score tussen 0 en 20:");
int score = int.Parse(Console.ReadLine());

while (score < 0 || score > 20)
{
    Console.WriteLine("Ongeldige score.");
}

Console.WriteLine($"Je score is {score}");
```

Voer deze code uit met een ongeldige score (bijvoorbeeld -5). Wat gebeurt er en waarom?

Pas de code aan zodat de gebruiker een geldige score kan invoeren als de vorige invoer ongeldig was.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Geef een score tussen 0 en 20:
5
Je score is 5
```

**Input:**

```
5
```

**Expected Output:**

```
Je score is 5
```

---

### Case 2

**Complete console output:**

```
Geef een score tussen 0 en 20:
-5
Ongeldige score.
Geef een score tussen 0 en 20:
10
Je score is 10
```

**Input:**

```
-5
10
```

**Expected Output:**

```
Ongeldige score.
Je score is 10
```

---

### Case 3

**Complete console output:**

```
Geef een score tussen 0 en 20:
25
Ongeldige score.
Geef een score tussen 0 en 20:
15
Je score is 15
```

**Input:**

```
25
15
```

**Expected Output:**

```
Ongeldige score.
Je score is 15
```

---

### Case 4

**Complete console output:**

```
Geef een score tussen 0 en 20:
0
Je score is 0
```

**Input:**

```
0
```

**Expected Output:**

```
Je score is 0
```

---

### Case 5

**Complete console output:**

```
Geef een score tussen 0 en 20:
20
Je score is 20
```

**Input:**

```
20
```

**Expected Output:**

```
Je score is 20
```
