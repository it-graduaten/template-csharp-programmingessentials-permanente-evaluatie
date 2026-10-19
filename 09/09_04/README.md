# 09_04

Je krijgt de volgende code te zien:

```csharp
int[] getallen = { -5, -2, -10 };

int hoogste = 0;

for (int i = 0; i < getallen.Length; i++)
{
    if (getallen[i] > hoogste)
    {
        hoogste = getallen[i];
    }
}

Console.WriteLine(hoogste);
```

Voer deze code uit. Wat is het probleem met deze code? Het programma toont `0`, maar `0` zit niet eens in de collectie.

Pas de code aan zodat deze correct werkt, ook voor arrays die alleen negatieve getallen bevatten.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
-2
```

**Input:**

```
(none)
```

**Expected Output:**

```
-2
```

---

### Case 2

**Complete console output:**

```
10
```

**Input:**

```
(none)
```

**Expected Output:**

```
10
```

---

### Case 3

**Complete console output:**

```
0
```

**Input:**

```
(none)
```

**Expected Output:**

```
0
```
