# 03_09

Een restaurant biedt de volgende kortingen aan:

- Op maandag t/m vrijdag tussen 11:00 en 14:00 uur: 10% korting op het lunchmenu.
- Op zaterdag en zondag tussen 12:00 en 16:00 uur: 15% korting op het weekendmenu.
- Groepen van meer dan 3 personen krijgen altijd extra 5% korting bovenop de bestaande korting.
- Op alle andere momenten geen korting.

Vraag de gebruiker om de dag van de week (als getal: 1=maandag, ..., 7=zondag), het uur van aankomst, het aantal personen en het totaalbedrag. Bereken en toon het eindbedrag na korting.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Description:** Run 1: args=5, 13, 10, 485.2290761177968


**Input:**

```
5
13
10
485.2290761177968
```

**Expected Output:**

```
Resultaat: 412.4447147001273
```

---

### Case 2

**Description:** Run 2: args=3, 22, 5, 145.5832543947127


**Input:**

```
3
22
5
145.5832543947127
```

**Expected Output:**

```
Resultaat: 138.30409167497706
```

---

### Case 3

**Description:** Run 3: args=7, 22, 6, 316.2348126716414


**Input:**

```
7
22
6
316.2348126716414
```

**Expected Output:**

```
Resultaat: 300.42307203805933
```

---

### Case 4

**Description:** Run 4: args=7, 2, 7, 29.80597279945468


**Input:**

```
7
2
7
29.80597279945468
```

**Expected Output:**

```
Resultaat: 28.315674159481944
```

---

### Case 5

**Description:** Run 5: args=2, 4, 7, 482.2912945539349


**Input:**

```
2
4
7
482.2912945539349
```

**Expected Output:**

```
Resultaat: 458.17672982623816
```

---

### Case 6

**Description:** Run 6: args=3, 6, 9, 280.72710429434613


**Input:**

```
3
6
9
280.72710429434613
```

**Expected Output:**

```
Resultaat: 266.6907490796288
```

---

### Case 7

**Description:** Run 7: args=5, 19, 10, 274.83529738531126


**Input:**

```
5
19
10
274.83529738531126
```

**Expected Output:**

```
Resultaat: 261.0935325160457
```

---

### Case 8

**Description:** Run 8: args=6, 18, 4, 149.2829532414699


**Input:**

```
6
18
4
149.2829532414699
```

**Expected Output:**

```
Resultaat: 141.8188055793964
```

---

### Case 9

**Description:** Run 9: args=2, 16, 6, 489.69643921354407


**Input:**

```
2
16
6
489.69643921354407
```

**Expected Output:**

```
Resultaat: 465.21161725286686
```

---

### Case 10

**Description:** Run 10: args=7, 10, 5, 423.4511774915855


**Input:**

```
7
10
5
423.4511774915855
```

**Expected Output:**

```
Resultaat: 402.2786186170062
```

---

### Case 11

**Description:** Run 11: args=4, 9, 2, 214.97144802124743


**Input:**

```
4
9
2
214.97144802124743
```

**Expected Output:**

```
Resultaat: 214.97144802124743
```

---

### Case 12

**Description:** Run 12: args=4, 9, 7, 95.28185372477824


**Input:**

```
4
9
7
95.28185372477824
```

**Expected Output:**

```
Resultaat: 90.51776103853933
```

---

### Case 13

**Description:** Run 13: args=7, 22, 8, 127.16934306791137


**Input:**

```
7
22
8
127.16934306791137
```

**Expected Output:**

```
Resultaat: 120.8108759145158
```

---

### Case 14

**Description:** Run 14: args=4, 11, 2, 491.6296007611533


**Input:**

```
4
11
2
491.6296007611533
```

**Expected Output:**

```
Resultaat: 442.466640685038
```

---

### Case 15

**Description:** Run 15: args=4, 10, 2, 136.9974693427081


**Input:**

```
4
10
2
136.9974693427081
```

**Expected Output:**

```
Resultaat: 136.9974693427081
```

---

### Case 16

**Description:** Run 16: args=5, 3, 5, 74.44246491201692


**Input:**

```
5
3
5
74.44246491201692
```

**Expected Output:**

```
Resultaat: 70.72034166641608
```

---

### Case 17

**Description:** Run 17: args=5, 17, 7, 263.47013225243944


**Input:**

```
5
17
7
263.47013225243944
```

**Expected Output:**

```
Resultaat: 250.29662563981748
```

---

### Case 18

**Description:** Run 18: args=1, 14, 3, 233.2107389844819


**Input:**

```
1
14
3
233.2107389844819
```

**Expected Output:**

```
Resultaat: 209.88966508603372
```

---

### Case 19

**Description:** Run 19: args=4, 7, 2, 180.28154381788116


**Input:**

```
4
7
2
180.28154381788116
```

**Expected Output:**

```
Resultaat: 180.28154381788116
```

---

### Case 20

**Description:** Run 20: args=1, 18, 8, 293.7936112718475


**Input:**

```
1
18
8
293.7936112718475
```

**Expected Output:**

```
Resultaat: 279.1039307082551
```

---

### Case 21

**Description:** Run 21: args=1, 23, 10, 313.08790398724403


**Input:**

```
1
23
10
313.08790398724403
```

**Expected Output:**

```
Resultaat: 297.4335087878818
```

---

### Case 22

**Description:** Run 22: args=1, 6, 7, 448.64313861192454


**Input:**

```
1
6
7
448.64313861192454
```

**Expected Output:**

```
Resultaat: 426.2109816813283
```

---

### Case 23

**Description:** Run 23: args=6, 4, 5, 92.16837703820671


**Input:**

```
6
4
5
92.16837703820671
```

**Expected Output:**

```
Resultaat: 87.55995818629638
```

---

### Case 24

**Description:** Run 24: args=6, 17, 1, 89.28075217137648


**Input:**

```
6
17
1
89.28075217137648
```

**Expected Output:**

```
Resultaat: 89.28075217137648
```

---

### Case 25

**Description:** Run 25: args=7, 20, 9, 319.7112341428076


**Input:**

```
7
20
9
319.7112341428076
```

**Expected Output:**

```
Resultaat: 303.7256724356672
```

---
