# 09_02

Je krijgt de volgende code te zien:

```csharp
List<int> getallen = new List<int>();
for (int i = 0; i <= 10; i++)
{
    Console.WriteLine($"Geef getal {i}: ");
    int getal = int.Parse(Console.ReadLine());
    getallen.Add(getal);
}

for (int i = 0; i <= getallen.Count; i++)
{
    Console.WriteLine($"Getal {i}: {getallen[i]}");
}
```

Voer deze code uit. Wat gebeurt er en waarom?

Pas de code aan zodat deze correct werkt zonder foutmelding.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
4
8
15
```

**Input:**

```
```

**Expected Output:**

```
4
8
15
```

---
