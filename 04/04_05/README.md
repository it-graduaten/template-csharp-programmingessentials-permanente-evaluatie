# 04_05

Een school wil een systeem bouwen om studenten te registreren en hun stemmen bij te houden. De school heeft exact twee kandidaat-borgmeesters: Anna en Bart.

Gebruik een List<string> om de namen van de gestemden bij te houden.

Vraag de gebruiker eerst hoeveel studenten er gaan stemmen. Vervolgens vraag je voor elke student:
1. De naam van de student.
2. Voor welke kandidaat ze stemmen (Anna of Bart).

Sla de naam van elke student op in de lijst. Tel ook het aantal stemmen voor Anna en Bart apart bij.

Tonen na alle stemmen: het totaal aantal stemmen, het aantal stemmen voor Anna, het aantal stemmen voor Bart, en wie gewonnen heeft.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 1
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): jaYi0
Totaal aantal stemmen: 1
Stemmen voor Anna: 0
Stemmen voor Bart: 1
Bart heeft gewonnen!
```

**Input:**

```
1
jaYi0
bart
2ILmq
anna
3JApO
bart
```

**Expected Output:**

```
Naam van student 1: Totaal aantal stemmen: 1
Stemmen voor Anna: 0
Stemmen voor Bart: 1
Bart heeft gewonnen!
```

---

### Case 2

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 1
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): cXTug
Totaal aantal stemmen: 1
Stemmen voor Anna: 0
Stemmen voor Bart: 1
Bart heeft gewonnen!
```

**Input:**

```
1
cXTug
bart
imNv4
anna
Glk0H
bart
```

**Expected Output:**

```
Naam van student 1: Totaal aantal stemmen: 1
Stemmen voor Anna: 0
Stemmen voor Bart: 1
Bart heeft gewonnen!
```

---

### Case 3

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 2
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): uHGoj
Naam van student 2: Voor welke kandidaat stem je? (Anna/Bart): anna
Totaal aantal stemmen: 2
Stemmen voor Anna: 2
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

**Input:**

```
2
uHGoj
anna
0HyVE
anna
Jvxc5
anna
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Totaal aantal stemmen: 2
Stemmen voor Anna: 2
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

---

### Case 4

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 3
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): v3S8o
Naam van student 2: Voor welke kandidaat stem je? (Anna/Bart): anna
Naam van student 3: Voor welke kandidaat stem je? (Anna/Bart): HLs45
Totaal aantal stemmen: 3
Stemmen voor Anna: 1
Stemmen voor Bart: 2
Bart heeft gewonnen!
```

**Input:**

```
3
v3S8o
anna
HLs45
bart
VbI4f
bart
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Naam van student 3: Totaal aantal stemmen: 3
Stemmen voor Anna: 1
Stemmen voor Bart: 2
Bart heeft gewonnen!
```

---

### Case 5

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 3
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): cNcdZ
Naam van student 2: Voor welke kandidaat stem je? (Anna/Bart): bart
Naam van student 3: Voor welke kandidaat stem je? (Anna/Bart): 96Uny
Totaal aantal stemmen: 3
Stemmen voor Anna: 1
Stemmen voor Bart: 2
Bart heeft gewonnen!
```

**Input:**

```
3
cNcdZ
bart
96Uny
bart
GSUTp
anna
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Naam van student 3: Totaal aantal stemmen: 3
Stemmen voor Anna: 1
Stemmen voor Bart: 2
Bart heeft gewonnen!
```

---

### Case 6

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 2
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): K2C9g
Naam van student 2: Voor welke kandidaat stem je? (Anna/Bart): anna
Totaal aantal stemmen: 2
Stemmen voor Anna: 1
Stemmen voor Bart: 1
Het is een gelijke stand!
```

**Input:**

```
2
K2C9g
anna
L8s43
bart
4nbJe
bart
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Totaal aantal stemmen: 2
Stemmen voor Anna: 1
Stemmen voor Bart: 1
Het is een gelijke stand!
```

---

### Case 7

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 1
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): KsZjb
Totaal aantal stemmen: 1
Stemmen voor Anna: 0
Stemmen voor Bart: 1
Bart heeft gewonnen!
```

**Input:**

```
1
KsZjb
bart
jMWe2
bart
s1kKc
bart
```

**Expected Output:**

```
Naam van student 1: Totaal aantal stemmen: 1
Stemmen voor Anna: 0
Stemmen voor Bart: 1
Bart heeft gewonnen!
```

---

### Case 8

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 2
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): Em1DE
Naam van student 2: Voor welke kandidaat stem je? (Anna/Bart): bart
Totaal aantal stemmen: 2
Stemmen voor Anna: 0
Stemmen voor Bart: 2
Bart heeft gewonnen!
```

**Input:**

```
2
Em1DE
bart
iT56q
bart
yxU38
anna
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Totaal aantal stemmen: 2
Stemmen voor Anna: 0
Stemmen voor Bart: 2
Bart heeft gewonnen!
```

---

### Case 9

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 2
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): SgzfJ
Naam van student 2: Voor welke kandidaat stem je? (Anna/Bart): anna
Totaal aantal stemmen: 2
Stemmen voor Anna: 2
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

**Input:**

```
2
SgzfJ
anna
nDQCO
anna
tRUHg
bart
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Totaal aantal stemmen: 2
Stemmen voor Anna: 2
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

---

### Case 10

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 3
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): fzp6H
Naam van student 2: Voor welke kandidaat stem je? (Anna/Bart): anna
Naam van student 3: Voor welke kandidaat stem je? (Anna/Bart): D4uMe
Totaal aantal stemmen: 3
Stemmen voor Anna: 3
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

**Input:**

```
3
fzp6H
anna
D4uMe
anna
XNJIx
anna
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Naam van student 3: Totaal aantal stemmen: 3
Stemmen voor Anna: 3
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

---

### Case 11

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 2
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): NUZyp
Naam van student 2: Voor welke kandidaat stem je? (Anna/Bart): anna
Totaal aantal stemmen: 2
Stemmen voor Anna: 2
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

**Input:**

```
2
NUZyp
anna
Mo6qD
anna
ZSBSo
bart
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Totaal aantal stemmen: 2
Stemmen voor Anna: 2
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

---

### Case 12

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 2
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): YQrHh
Naam van student 2: Voor welke kandidaat stem je? (Anna/Bart): bart
Totaal aantal stemmen: 2
Stemmen voor Anna: 0
Stemmen voor Bart: 2
Bart heeft gewonnen!
```

**Input:**

```
2
YQrHh
bart
2Skhi
bart
nnkUs
anna
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Totaal aantal stemmen: 2
Stemmen voor Anna: 0
Stemmen voor Bart: 2
Bart heeft gewonnen!
```

---

### Case 13

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 2
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): k1P6J
Naam van student 2: Voor welke kandidaat stem je? (Anna/Bart): anna
Totaal aantal stemmen: 2
Stemmen voor Anna: 2
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

**Input:**

```
2
k1P6J
anna
y5zXK
anna
NzpaN
anna
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Totaal aantal stemmen: 2
Stemmen voor Anna: 2
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

---

### Case 14

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 3
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): euEq9
Naam van student 2: Voor welke kandidaat stem je? (Anna/Bart): bart
Naam van student 3: Voor welke kandidaat stem je? (Anna/Bart): voxN9
Totaal aantal stemmen: 3
Stemmen voor Anna: 0
Stemmen voor Bart: 3
Bart heeft gewonnen!
```

**Input:**

```
3
euEq9
bart
voxN9
bart
igK4a
bart
```

**Expected Output:**

```
Naam van student 1: Naam van student 2: Naam van student 3: Totaal aantal stemmen: 3
Stemmen voor Anna: 0
Stemmen voor Bart: 3
Bart heeft gewonnen!
```

---

### Case 15

**Complete console output:**

```
Hoeveel studenten gaan stemmen? 1
Naam van student 1: Voor welke kandidaat stem je? (Anna/Bart): BnxTr
Totaal aantal stemmen: 1
Stemmen voor Anna: 1
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

**Input:**

```
1
BnxTr
anna
2tg5W
bart
1kbNO
anna
```

**Expected Output:**

```
Naam van student 1: Totaal aantal stemmen: 1
Stemmen voor Anna: 1
Stemmen voor Bart: 0
Anna heeft gewonnen!
```

---
