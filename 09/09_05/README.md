# 09_05

Je krijgt de volgende code te zien:

```csharp
Console.WriteLine("Hoeveel scores wil je invoeren?");
int aantal = int.Parse(Console.ReadLine());

int[] scores = new int[aantal];
int totaal = 0;

for (int i = 0; i < aantal; i++)
{
    Console.Write($"Score {i + 1}: ");
    scores[i] = int.Parse(Console.ReadLine());
}

for (int i = 0; i <= aantal; i++)
{
    if (scores[i] >= 10)
    {
        aantalGeslaagd++;
    }
}

Console.WriteLine($"Aantal geslaagd: {aantalGeslaagd}");
```

Er zitten meerdere fouten in deze code. Voer de code uit en identificeer alle problemen.

De bedoeling is: de gebruiker voert een aantal scores in, en het programma telt hoeveel scores er minstens 10 zijn.

Pas de code aan zodat deze correct werkt.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel scores wil je invoeren?
3
Score 1: 8
Score 2: 12
Score 3: 15
Aantal geslaagd: 2
```

**Input:**

```
3
8
12
15
```

**Expected Output:**

```
Aantal geslaagd: 2
```

---

### Case 2

**Complete console output:**

```
Hoeveel scores wil je invoeren?
4
Score 1: 10
Score 2: 15
Score 3: 12
Score 4: 18
Aantal geslaagd: 4
```

**Input:**

```
4
10
15
12
18
```

**Expected Output:**

```
Aantal geslaagd: 4
```

---

### Case 3

**Complete console output:**

```
Hoeveel scores wil je invoeren?
2
Score 1: 5
Score 2: 3
Aantal geslaagd: 0
```

**Input:**

```
2
5
3
```

**Expected Output:**

```
Aantal geslaagd: 0
```

---

### Case 4

**Complete console output:**

```
Hoeveel scores wil je invoeren?
1
Score 1: 10
Aantal geslaagd: 1
```

**Input:**

```
1
10
```

**Expected Output:**

```
Aantal geslaagd: 1
```

---

### Case 5

**Complete console output:**

```
Hoeveel scores wil je invoeren?
3
Score 1: 9
Score 2: 10
Score 3: 11
Aantal geslaagd: 2
```

**Input:**

```
3
9
10
11
```

**Expected Output:**

```
Aantal geslaagd: 2
```
