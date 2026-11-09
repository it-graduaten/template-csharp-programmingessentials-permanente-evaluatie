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

Pas de code aan zodat deze correct werkt. Ter info: een score van 10 of hoger is geslaagd.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel scores wil je invoeren?
2
Score 1: 14
Score 2: 12
Aantal geslaagd: 2
```

**Input:**

```
2
14
12
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
6
Score 1: 9
Score 2: 14
Score 3: 7
Score 4: 2
Score 5: 11
Score 6: 5
Aantal geslaagd: 2
```

**Input:**

```
6
9
14
7
2
11
5
```

**Expected Output:**

```
Aantal geslaagd: 2
```

---

### Case 3

**Complete console output:**

```
Hoeveel scores wil je invoeren?
1
Score 1: 15
Aantal geslaagd: 1
```

**Input:**

```
1
15
```

**Expected Output:**

```
Aantal geslaagd: 1
```

---

### Case 4

**Complete console output:**

```
Hoeveel scores wil je invoeren?
2
Score 1: 14
Score 2: 17
Aantal geslaagd: 2
```

**Input:**

```
2
14
17
```

**Expected Output:**

```
Aantal geslaagd: 2
```

---

### Case 5

**Complete console output:**

```
Hoeveel scores wil je invoeren?
3
Score 1: 15
Score 2: 13
Score 3: 0
Aantal geslaagd: 2
```

**Input:**

```
3
15
13
0
```

**Expected Output:**

```
Aantal geslaagd: 2
```

---

### Case 6

**Complete console output:**

```
Hoeveel scores wil je invoeren?
9
Score 1: 13
Score 2: 15
Score 3: 14
Score 4: 0
Score 5: 20
Score 6: 9
Score 7: 20
Score 8: 8
Score 9: 1
Aantal geslaagd: 5
```

**Input:**

```
9
13
15
14
0
20
9
20
8
1
```

**Expected Output:**

```
Aantal geslaagd: 5
```

---

### Case 7

**Complete console output:**

```
Hoeveel scores wil je invoeren?
7
Score 1: 9
Score 2: 17
Score 3: 8
Score 4: 17
Score 5: 20
Score 6: 8
Score 7: 15
Aantal geslaagd: 4
```

**Input:**

```
7
9
17
8
17
20
8
15
```

**Expected Output:**

```
Aantal geslaagd: 4
```

---

### Case 8

**Complete console output:**

```
Hoeveel scores wil je invoeren?
1
Score 1: 5
Aantal geslaagd: 0
```

**Input:**

```
1
5
```

**Expected Output:**

```
Aantal geslaagd: 0
```

---

### Case 9

**Complete console output:**

```
Hoeveel scores wil je invoeren?
5
Score 1: 6
Score 2: 10
Score 3: 20
Score 4: 18
Score 5: 8
Aantal geslaagd: 3
```

**Input:**

```
5
6
10
20
18
8
```

**Expected Output:**

```
Aantal geslaagd: 3
```

---

### Case 10

**Complete console output:**

```
Hoeveel scores wil je invoeren?
1
Score 1: 15
Aantal geslaagd: 1
```

**Input:**

```
1
15
```

**Expected Output:**

```
Aantal geslaagd: 1
```

---

### Case 11

**Complete console output:**

```
Hoeveel scores wil je invoeren?
6
Score 1: 19
Score 2: 9
Score 3: 6
Score 4: 2
Score 5: 17
Score 6: 16
Aantal geslaagd: 3
```

**Input:**

```
6
19
9
6
2
17
16
```

**Expected Output:**

```
Aantal geslaagd: 3
```

---

### Case 12

**Complete console output:**

```
Hoeveel scores wil je invoeren?
7
Score 1: 12
Score 2: 5
Score 3: 12
Score 4: 8
Score 5: 15
Score 6: 6
Score 7: 0
Aantal geslaagd: 3
```

**Input:**

```
7
12
5
12
8
15
6
0
```

**Expected Output:**

```
Aantal geslaagd: 3
```

---

### Case 13

**Complete console output:**

```
Hoeveel scores wil je invoeren?
6
Score 1: 1
Score 2: 4
Score 3: 0
Score 4: 16
Score 5: 20
Score 6: 8
Aantal geslaagd: 2
```

**Input:**

```
6
1
4
0
16
20
8
```

**Expected Output:**

```
Aantal geslaagd: 2
```

---

### Case 14

**Complete console output:**

```
Hoeveel scores wil je invoeren?
5
Score 1: 17
Score 2: 16
Score 3: 6
Score 4: 6
Score 5: 11
Aantal geslaagd: 3
```

**Input:**

```
5
17
16
6
6
11
```

**Expected Output:**

```
Aantal geslaagd: 3
```

---

### Case 15

**Complete console output:**

```
Hoeveel scores wil je invoeren?
4
Score 1: 5
Score 2: 5
Score 3: 11
Score 4: 4
Aantal geslaagd: 1
```

**Input:**

```
4
5
5
11
4
```

**Expected Output:**

```
Aantal geslaagd: 1
```

---
