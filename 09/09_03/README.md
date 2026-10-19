# 09_03

Je krijgt de volgende code te zien:

```csharp
int[] temperaturen = { 18, 22, 16, 25 };

int totaal = 0;

for (int i = 0; i < temperaturen.Length; i++)
{
    totaal = temperaturen[i];
}

Console.WriteLine(totaal);
```

Voer deze code uit en traceer de waarde van `totaal` stap voor stap.

Wat is het probleem met deze code? De bedoeling is om alle temperaturen op te tellen, maar het resultaat is niet correct.

Pas de code aan zodat deze correct werkt.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
81
```

**Input:**

```
(none)
```

**Expected Output:**

```
81
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
-7
```

**Input:**

```
(none)
```

**Expected Output:**

```
-7
```
