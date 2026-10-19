# 09_10

Je krijgt de volgende code te zien:

```csharp
Console.WriteLine("Hoeveel getallen wil je invoeren?");
int aantal = int.Parse(Console.ReadLine());

int[] getallen = new int[aantal];
int totaal = 0;
int hoogste = 0;

for (int i = 0; i < aantal; i++)
{
    Console.Write($"Getal {i + 1}: ");
    getallen[i] = int.Parse(Console.ReadLine());
}

for (int i = 0; i <= aantal; i++)
{
    totaal += getallen[i];
}

for (int i = 0; i < aantal; i++)
{
    if (getallen[i] > hoogste)
    {
        hoogste = getallen[i];
    }
}

Console.WriteLine($"Totaal: {totaal}");
Console.WriteLine($"Hoogste: {hoogste}");
```

Er zitten meerdere fouten in deze code. De bedoeling is: de gebruiker voert een aantal getallen in, en het programma berekent het totaal en bepaalt het hoogste getal.

Voer de code uit en identificeer alle problemen. Pas de code aan zodat deze correct werkt, ook voor arrays die alleen negatieve getallen bevatten.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 3
Getal 1: 10
Getal 2: 20
Getal 3: 5
Totaal: 35
Hoogste: 20
```

**Input:**

```
3
10
20
5
```

**Expected Output:**

```
Totaal: 35
Hoogste: 20
```

---

### Case 2

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 4
Getal 1: -5
Getal 2: -2
Getal 3: -10
Getal 4: 0
Totaal: -17
Hoogste: 0
```

**Input:**

```
4
-5
-2
-10
0
```

**Expected Output:**

```
Totaal: -17
Hoogste: 0
```

---

### Case 3

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 1
Getal 1: 42
Totaal: 42
Hoogste: 42
```

**Input:**

```
1
42
```

**Expected Output:**

```
Totaal: 42
Hoogste: 42
```

---

### Case 4

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 3
Getal 1: -100
Getal 2: 100
Getal 3: 0
Totaal: 0
Hoogste: 100
```

**Input:**

```
3
-100
100
0
```

**Expected Output:**

```
Totaal: 0
Hoogste: 100
```

---

### Case 5

**Complete console output:**

```
Hoeveel getallen wil je invoeren? 2
Getal 1: 7
Getal 2: 7
Totaal: 14
Hoogste: 7
```

**Input:**

```
2
7
7
```

**Expected Output:**

```
Totaal: 14
Hoogste: 7
```
