# 03_05

Een school hanteert de volgende regels voor het toekennen van een studierichting:

- Als de student gemiddeld 75% of meer haalt én wiskunde heeft gevolgd, kan de student kiezen voor de richting "Wetenschap".
- Als de student gemiddeld 75% of meer haalt maar wiskunde niet heeft gevolgd, kan de student kiezen voor de richting "Letteren".
- Als de student gemiddeld tussen 60% en 74% haalt, wordt de student doorverwezen naar de richting "Techniek".
- Als de student minder dan 60% haalt, wordt de student doorverwezen naar de richtingskeuzebegeleiding.

Vraag de gebruiker om zijn gemiddelde percentage en of hij/zij wiskunde heeft gevolgd (ja/nee). Toon de aanbevolen studierichting.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Geef je gemiddelde percentage: 3
Heb je wiskunde gevolgd? (ja/nee): nee
richtingskeuzebegeleiding
```

**Input:**

```
3
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 2

**Complete console output:**

```
Geef je gemiddelde percentage: 74
Heb je wiskunde gevolgd? (ja/nee): nee
Techniek
```

**Input:**

```
74
nee
```

**Expected Output:**

```
Techniek
```

---

### Case 3

**Complete console output:**

```
Geef je gemiddelde percentage: 56
Heb je wiskunde gevolgd? (ja/nee): ja
richtingskeuzebegeleiding
```

**Input:**

```
56
ja
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 4

**Complete console output:**

```
Geef je gemiddelde percentage: 33
Heb je wiskunde gevolgd? (ja/nee): nee
richtingskeuzebegeleiding
```

**Input:**

```
33
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 5

**Complete console output:**

```
Geef je gemiddelde percentage: 23
Heb je wiskunde gevolgd? (ja/nee): nee
richtingskeuzebegeleiding
```

**Input:**

```
23
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 6

**Complete console output:**

```
Geef je gemiddelde percentage: 78
Heb je wiskunde gevolgd? (ja/nee): ja
Wetenschap
```

**Input:**

```
78
ja
```

**Expected Output:**

```
Wetenschap
```

---

### Case 7

**Complete console output:**

```
Geef je gemiddelde percentage: 86
Heb je wiskunde gevolgd? (ja/nee): ja
Wetenschap
```

**Input:**

```
86
ja
```

**Expected Output:**

```
Wetenschap
```

---

### Case 8

**Complete console output:**

```
Geef je gemiddelde percentage: 2
Heb je wiskunde gevolgd? (ja/nee): nee
richtingskeuzebegeleiding
```

**Input:**

```
2
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 9

**Complete console output:**

```
Geef je gemiddelde percentage: 92
Heb je wiskunde gevolgd? (ja/nee): ja
Wetenschap
```

**Input:**

```
92
ja
```

**Expected Output:**

```
Wetenschap
```

---

### Case 10

**Complete console output:**

```
Geef je gemiddelde percentage: 11
Heb je wiskunde gevolgd? (ja/nee): nee
richtingskeuzebegeleiding
```

**Input:**

```
11
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 11

**Complete console output:**

```
Geef je gemiddelde percentage: 99
Heb je wiskunde gevolgd? (ja/nee): nee
Letteren
```

**Input:**

```
99
nee
```

**Expected Output:**

```
Letteren
```

---

### Case 12

**Complete console output:**

```
Geef je gemiddelde percentage: 53
Heb je wiskunde gevolgd? (ja/nee): nee
richtingskeuzebegeleiding
```

**Input:**

```
53
nee
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 13

**Complete console output:**

```
Geef je gemiddelde percentage: 67
Heb je wiskunde gevolgd? (ja/nee): ja
Techniek
```

**Input:**

```
67
ja
```

**Expected Output:**

```
Techniek
```

---

### Case 14

**Complete console output:**

```
Geef je gemiddelde percentage: 32
Heb je wiskunde gevolgd? (ja/nee): ja
richtingskeuzebegeleiding
```

**Input:**

```
32
ja
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 15

**Complete console output:**

```
Geef je gemiddelde percentage: 95
Heb je wiskunde gevolgd? (ja/nee): ja
Wetenschap
```

**Input:**

```
95
ja
```

**Expected Output:**

```
Wetenschap
```

---

### Case 16

**Complete console output:**

```
Geef je gemiddelde percentage: 76
Heb je wiskunde gevolgd? (ja/nee): nee
Letteren
```

**Input:**

```
76
nee
```

**Expected Output:**

```
Letteren
```

---

### Case 17

**Complete console output:**

```
Geef je gemiddelde percentage: 44
Heb je wiskunde gevolgd? (ja/nee): ja
richtingskeuzebegeleiding
```

**Input:**

```
44
ja
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 18

**Complete console output:**

```
Geef je gemiddelde percentage: 98
Heb je wiskunde gevolgd? (ja/nee): nee
Letteren
```

**Input:**

```
98
nee
```

**Expected Output:**

```
Letteren
```

---

### Case 19

**Complete console output:**

```
Geef je gemiddelde percentage: 73
Heb je wiskunde gevolgd? (ja/nee): nee
Techniek
```

**Input:**

```
73
nee
```

**Expected Output:**

```
Techniek
```

---

### Case 20

**Complete console output:**

```
Geef je gemiddelde percentage: 71
Heb je wiskunde gevolgd? (ja/nee): nee
Techniek
```

**Input:**

```
71
nee
```

**Expected Output:**

```
Techniek
```

---

### Case 21

**Complete console output:**

```
Geef je gemiddelde percentage: 56
Heb je wiskunde gevolgd? (ja/nee): ja
richtingskeuzebegeleiding
```

**Input:**

```
56
ja
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---

### Case 22

**Complete console output:**

```
Geef je gemiddelde percentage: 72
Heb je wiskunde gevolgd? (ja/nee): nee
Techniek
```

**Input:**

```
72
nee
```

**Expected Output:**

```
Techniek
```

---

### Case 23

**Complete console output:**

```
Geef je gemiddelde percentage: 78
Heb je wiskunde gevolgd? (ja/nee): nee
Letteren
```

**Input:**

```
78
nee
```

**Expected Output:**

```
Letteren
```

---

### Case 24

**Complete console output:**

```
Geef je gemiddelde percentage: 63
Heb je wiskunde gevolgd? (ja/nee): ja
Techniek
```

**Input:**

```
63
ja
```

**Expected Output:**

```
Techniek
```

---

### Case 25

**Complete console output:**

```
Geef je gemiddelde percentage: 25
Heb je wiskunde gevolgd? (ja/nee): ja
richtingskeuzebegeleiding
```

**Input:**

```
25
ja
```

**Expected Output:**

```
richtingskeuzebegeleiding
```

---
