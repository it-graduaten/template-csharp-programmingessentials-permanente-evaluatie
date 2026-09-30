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

**Complete console output:**

```
Geef de dag van de week (1-7): 4
Geef het uur van aankomst: 17
Geef het aantal personen: 1
Geef het totaalbedrag: 324.9158981730759
Resultaat: 324.9158981730759
```

**Input:**

```
4
17
1
324.9158981730759
```

**Expected Output:**

```
Resultaat: 324.9158981730759
```

---

### Case 2

**Complete console output:**

```
Geef de dag van de week (1-7): 3
Geef het uur van aankomst: 11
Geef het aantal personen: 8
Geef het totaalbedrag: 250.36433912544896
Resultaat: 212.80968825663163
```

**Input:**

```
3
11
8
250.36433912544896
```

**Expected Output:**

```
Resultaat: 212.80968825663163
```

---

### Case 3

**Complete console output:**

```
Geef de dag van de week (1-7): 2
Geef het uur van aankomst: 8
Geef het aantal personen: 7
Geef het totaalbedrag: 162.27595578673458
Resultaat: 154.16215799739786
```

**Input:**

```
2
8
7
162.27595578673458
```

**Expected Output:**

```
Resultaat: 154.16215799739786
```

---

### Case 4

**Complete console output:**

```
Geef de dag van de week (1-7): 6
Geef het uur van aankomst: 20
Geef het aantal personen: 5
Geef het totaalbedrag: 257.9810625300769
Resultaat: 245.08200940357304
```

**Input:**

```
6
20
5
257.9810625300769
```

**Expected Output:**

```
Resultaat: 245.08200940357304
```

---

### Case 5

**Complete console output:**

```
Geef de dag van de week (1-7): 3
Geef het uur van aankomst: 10
Geef het aantal personen: 6
Geef het totaalbedrag: 36.766197601018675
Resultaat: 34.92788772096774
```

**Input:**

```
3
10
6
36.766197601018675
```

**Expected Output:**

```
Resultaat: 34.92788772096774
```

---

### Case 6

**Complete console output:**

```
Geef de dag van de week (1-7): 5
Geef het uur van aankomst: 1
Geef het aantal personen: 8
Geef het totaalbedrag: 285.6878895167768
Resultaat: 271.40349504093797
```

**Input:**

```
5
1
8
285.6878895167768
```

**Expected Output:**

```
Resultaat: 271.40349504093797
```

---

### Case 7

**Complete console output:**

```
Geef de dag van de week (1-7): 5
Geef het uur van aankomst: 22
Geef het aantal personen: 4
Geef het totaalbedrag: 291.09128432640176
Resultaat: 276.53672011008166
```

**Input:**

```
5
22
4
291.09128432640176
```

**Expected Output:**

```
Resultaat: 276.53672011008166
```

---

### Case 8

**Complete console output:**

```
Geef de dag van de week (1-7): 3
Geef het uur van aankomst: 10
Geef het aantal personen: 8
Geef het totaalbedrag: 119.78778494363299
Resultaat: 113.79839569645134
```

**Input:**

```
3
10
8
119.78778494363299
```

**Expected Output:**

```
Resultaat: 113.79839569645134
```

---

### Case 9

**Complete console output:**

```
Geef de dag van de week (1-7): 7
Geef het uur van aankomst: 17
Geef het aantal personen: 5
Geef het totaalbedrag: 282.5461500366628
Resultaat: 268.4188425348297
```

**Input:**

```
7
17
5
282.5461500366628
```

**Expected Output:**

```
Resultaat: 268.4188425348297
```

---

### Case 10

**Complete console output:**

```
Geef de dag van de week (1-7): 2
Geef het uur van aankomst: 23
Geef het aantal personen: 9
Geef het totaalbedrag: 245.16980203172704
Resultaat: 232.9113119301407
```

**Input:**

```
2
23
9
245.16980203172704
```

**Expected Output:**

```
Resultaat: 232.9113119301407
```

---

### Case 11

**Complete console output:**

```
Geef de dag van de week (1-7): 1
Geef het uur van aankomst: 9
Geef het aantal personen: 5
Geef het totaalbedrag: 89.10724559347938
Resultaat: 84.65188331380541
```

**Input:**

```
1
9
5
89.10724559347938
```

**Expected Output:**

```
Resultaat: 84.65188331380541
```

---

### Case 12

**Complete console output:**

```
Geef de dag van de week (1-7): 7
Geef het uur van aankomst: 15
Geef het aantal personen: 8
Geef het totaalbedrag: 51.71803267661474
Resultaat: 41.37442614129179
```

**Input:**

```
7
15
8
51.71803267661474
```

**Expected Output:**

```
Resultaat: 41.37442614129179
```

---

### Case 13

**Complete console output:**

```
Geef de dag van de week (1-7): 1
Geef het uur van aankomst: 20
Geef het aantal personen: 1
Geef het totaalbedrag: 441.76213835387506
Resultaat: 441.76213835387506
```

**Input:**

```
1
20
1
441.76213835387506
```

**Expected Output:**

```
Resultaat: 441.76213835387506
```

---

### Case 14

**Complete console output:**

```
Geef de dag van de week (1-7): 2
Geef het uur van aankomst: 2
Geef het aantal personen: 5
Geef het totaalbedrag: 55.1690441640985
Resultaat: 52.41059195589358
```

**Input:**

```
2
2
5
55.1690441640985
```

**Expected Output:**

```
Resultaat: 52.41059195589358
```

---

### Case 15

**Complete console output:**

```
Geef de dag van de week (1-7): 4
Geef het uur van aankomst: 20
Geef het aantal personen: 8
Geef het totaalbedrag: 282.64901943686107
Resultaat: 268.516568465018
```

**Input:**

```
4
20
8
282.64901943686107
```

**Expected Output:**

```
Resultaat: 268.516568465018
```

---

### Case 16

**Complete console output:**

```
Geef de dag van de week (1-7): 5
Geef het uur van aankomst: 9
Geef het aantal personen: 6
Geef het totaalbedrag: 206.53522188694922
Resultaat: 196.20846079260176
```

**Input:**

```
5
9
6
206.53522188694922
```

**Expected Output:**

```
Resultaat: 196.20846079260176
```

---

### Case 17

**Complete console output:**

```
Geef de dag van de week (1-7): 7
Geef het uur van aankomst: 8
Geef het aantal personen: 7
Geef het totaalbedrag: 221.9805930256142
Resultaat: 210.8815633743335
```

**Input:**

```
7
8
7
221.9805930256142
```

**Expected Output:**

```
Resultaat: 210.8815633743335
```

---

### Case 18

**Complete console output:**

```
Geef de dag van de week (1-7): 2
Geef het uur van aankomst: 13
Geef het aantal personen: 2
Geef het totaalbedrag: 333.77130036975257
Resultaat: 300.3941703327773
```

**Input:**

```
2
13
2
333.77130036975257
```

**Expected Output:**

```
Resultaat: 300.3941703327773
```

---

### Case 19

**Complete console output:**

```
Geef de dag van de week (1-7): 2
Geef het uur van aankomst: 8
Geef het aantal personen: 4
Geef het totaalbedrag: 352.2813173623483
Resultaat: 334.6672514942309
```

**Input:**

```
2
8
4
352.2813173623483
```

**Expected Output:**

```
Resultaat: 334.6672514942309
```

---

### Case 20

**Complete console output:**

```
Geef de dag van de week (1-7): 4
Geef het uur van aankomst: 17
Geef het aantal personen: 10
Geef het totaalbedrag: 387.65530517895957
Resultaat: 368.2725399200116
```

**Input:**

```
4
17
10
387.65530517895957
```

**Expected Output:**

```
Resultaat: 368.2725399200116
```

---

### Case 21

**Complete console output:**

```
Geef de dag van de week (1-7): 6
Geef het uur van aankomst: 1
Geef het aantal personen: 10
Geef het totaalbedrag: 239.1223764128644
Resultaat: 227.1662575922212
```

**Input:**

```
6
1
10
239.1223764128644
```

**Expected Output:**

```
Resultaat: 227.1662575922212
```

---

### Case 22

**Complete console output:**

```
Geef de dag van de week (1-7): 6
Geef het uur van aankomst: 8
Geef het aantal personen: 2
Geef het totaalbedrag: 430.9545573266028
Resultaat: 430.9545573266028
```

**Input:**

```
6
8
2
430.9545573266028
```

**Expected Output:**

```
Resultaat: 430.9545573266028
```

---

### Case 23

**Complete console output:**

```
Geef de dag van de week (1-7): 1
Geef het uur van aankomst: 15
Geef het aantal personen: 8
Geef het totaalbedrag: 425.41977647908794
Resultaat: 404.14878765513356
```

**Input:**

```
1
15
8
425.41977647908794
```

**Expected Output:**

```
Resultaat: 404.14878765513356
```

---

### Case 24

**Complete console output:**

```
Geef de dag van de week (1-7): 4
Geef het uur van aankomst: 5
Geef het aantal personen: 10
Geef het totaalbedrag: 330.7662937819589
Resultaat: 314.22797909286095
```

**Input:**

```
4
5
10
330.7662937819589
```

**Expected Output:**

```
Resultaat: 314.22797909286095
```

---

### Case 25

**Complete console output:**

```
Geef de dag van de week (1-7): 4
Geef het uur van aankomst: 2
Geef het aantal personen: 4
Geef het totaalbedrag: 249.65224969552344
Resultaat: 237.16963721074725
```

**Input:**

```
4
2
4
249.65224969552344
```

**Expected Output:**

```
Resultaat: 237.16963721074725
```

---
