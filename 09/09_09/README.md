# 09_09

Je krijgt de volgende code te zien:

```csharp
int Verdubbel(int getal)
{
    return getal * 2;
}

Console.WriteLine("Voer een getal in:");
int waarde = int.Parse(Console.ReadLine());

Verdubbel(waarde);

Console.WriteLine($"Het verdubbelde getal is: {waarde}");
```

Voer deze code uit. Wat is het probleem met deze code? Het programma toont niet het verdubbelde getal.

Pas de code aan zodat deze correct werkt.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Voer een getal in:
5
Het verdubbelde getal is: 10
```

**Input:**

```
5
```

**Expected Output:**

```
Het verdubbelde getal is: 10
```

---

### Case 2

**Complete console output:**

```
Voer een getal in:
10
Het verdubbelde getal is: 20
```

**Input:**

```
10
```

**Expected Output:**

```
Het verdubbelde getal is: 20
```

---

### Case 3

**Complete console output:**

```
Voer een getal in:
-3
Het verdubbelde getal is: -6
```

**Input:**

```
-3
```

**Expected Output:**

```
Het verdubbelde getal is: -6
```

---

### Case 4

**Complete console output:**

```
Voer een getal in:
0
Het verdubbelde getal is: 0
```

**Input:**

```
0
```

**Expected Output:**

```
Het verdubbelde getal is: 0
```

---

### Case 5

**Complete console output:**

```
Voer een getal in:
7
Het verdubbelde getal is: 14
```

**Input:**

```
7
```

**Expected Output:**

```
Het verdubbelde getal is: 14
```
