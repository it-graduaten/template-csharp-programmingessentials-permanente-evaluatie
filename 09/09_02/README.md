# 09_02

Je krijgt de volgende code te zien:

```csharp
List<int> getallen = new List<int>();
for (int i = 0; i <= 10; i++)
{
    Console.WriteLine($"Geef getal {i}: ");
    int getal = int.Parse(Console.ReadLine());
    getallen.Add(getal);
}

for (int i = 0; i <= getallen.Count; i++)
{
    Console.WriteLine($"Getal {i}: {getallen[i]}");
}
```

Voer deze code uit. Wat gebeurt er en waarom?

Pas de code aan zodat deze correct werkt zonder foutmelding.

## Fuzz Test Cases

Below are the automatically generated input/output expectations.

---

### Case 1

**Complete console output:**

```
Geef getal 0: 
92
Geef getal 1: 
51
Geef getal 2: 
25
Geef getal 3: 
86
Geef getal 4: 
6
Geef getal 5: 
4
Geef getal 6: 
0
Geef getal 7: 
81
Geef getal 8: 
17
Geef getal 9: 
17
Getal 0: 92
Getal 1: 51
Getal 2: 25
Getal 3: 86
Getal 4: 6
Getal 5: 4
Getal 6: 0
Getal 7: 81
Getal 8: 17
Getal 9: 17
```

**Input:**

```
92
51
25
86
6
4
0
81
17
17
```

**Expected Output:**

```
Getal 0: 92
Getal 1: 51
Getal 2: 25
Getal 3: 86
Getal 4: 6
Getal 5: 4
Getal 6: 0
Getal 7: 81
Getal 8: 17
Getal 9: 17
```

---

### Case 2

**Complete console output:**

```
Geef getal 0: 
19
Geef getal 1: 
38
Geef getal 2: 
20
Geef getal 3: 
73
Geef getal 4: 
54
Geef getal 5: 
16
Geef getal 6: 
90
Geef getal 7: 
15
Geef getal 8: 
16
Geef getal 9: 
54
Getal 0: 19
Getal 1: 38
Getal 2: 20
Getal 3: 73
Getal 4: 54
Getal 5: 16
Getal 6: 90
Getal 7: 15
Getal 8: 16
Getal 9: 54
```

**Input:**

```
19
38
20
73
54
16
90
15
16
54
```

**Expected Output:**

```
Getal 0: 19
Getal 1: 38
Getal 2: 20
Getal 3: 73
Getal 4: 54
Getal 5: 16
Getal 6: 90
Getal 7: 15
Getal 8: 16
Getal 9: 54
```

---

### Case 3

**Complete console output:**

```
Geef getal 0: 
92
Geef getal 1: 
95
Geef getal 2: 
70
Geef getal 3: 
97
Geef getal 4: 
43
Geef getal 5: 
31
Geef getal 6: 
25
Geef getal 7: 
40
Geef getal 8: 
56
Geef getal 9: 
51
Getal 0: 92
Getal 1: 95
Getal 2: 70
Getal 3: 97
Getal 4: 43
Getal 5: 31
Getal 6: 25
Getal 7: 40
Getal 8: 56
Getal 9: 51
```

**Input:**

```
92
95
70
97
43
31
25
40
56
51
```

**Expected Output:**

```
Getal 0: 92
Getal 1: 95
Getal 2: 70
Getal 3: 97
Getal 4: 43
Getal 5: 31
Getal 6: 25
Getal 7: 40
Getal 8: 56
Getal 9: 51
```

---

### Case 4

**Complete console output:**

```
Geef getal 0: 
22
Geef getal 1: 
40
Geef getal 2: 
53
Geef getal 3: 
68
Geef getal 4: 
38
Geef getal 5: 
66
Geef getal 6: 
93
Geef getal 7: 
12
Geef getal 8: 
74
Geef getal 9: 
8
Getal 0: 22
Getal 1: 40
Getal 2: 53
Getal 3: 68
Getal 4: 38
Getal 5: 66
Getal 6: 93
Getal 7: 12
Getal 8: 74
Getal 9: 8
```

**Input:**

```
22
40
53
68
38
66
93
12
74
8
```

**Expected Output:**

```
Getal 0: 22
Getal 1: 40
Getal 2: 53
Getal 3: 68
Getal 4: 38
Getal 5: 66
Getal 6: 93
Getal 7: 12
Getal 8: 74
Getal 9: 8
```

---

### Case 5

**Complete console output:**

```
Geef getal 0: 
31
Geef getal 1: 
15
Geef getal 2: 
14
Geef getal 3: 
29
Geef getal 4: 
12
Geef getal 5: 
53
Geef getal 6: 
77
Geef getal 7: 
39
Geef getal 8: 
3
Geef getal 9: 
96
Getal 0: 31
Getal 1: 15
Getal 2: 14
Getal 3: 29
Getal 4: 12
Getal 5: 53
Getal 6: 77
Getal 7: 39
Getal 8: 3
Getal 9: 96
```

**Input:**

```
31
15
14
29
12
53
77
39
3
96
```

**Expected Output:**

```
Getal 0: 31
Getal 1: 15
Getal 2: 14
Getal 3: 29
Getal 4: 12
Getal 5: 53
Getal 6: 77
Getal 7: 39
Getal 8: 3
Getal 9: 96
```

---

### Case 6

**Complete console output:**

```
Geef getal 0: 
64
Geef getal 1: 
84
Geef getal 2: 
44
Geef getal 3: 
31
Geef getal 4: 
0
Geef getal 5: 
71
Geef getal 6: 
14
Geef getal 7: 
87
Geef getal 8: 
45
Geef getal 9: 
96
Getal 0: 64
Getal 1: 84
Getal 2: 44
Getal 3: 31
Getal 4: 0
Getal 5: 71
Getal 6: 14
Getal 7: 87
Getal 8: 45
Getal 9: 96
```

**Input:**

```
64
84
44
31
0
71
14
87
45
96
```

**Expected Output:**

```
Getal 0: 64
Getal 1: 84
Getal 2: 44
Getal 3: 31
Getal 4: 0
Getal 5: 71
Getal 6: 14
Getal 7: 87
Getal 8: 45
Getal 9: 96
```

---

### Case 7

**Complete console output:**

```
Geef getal 0: 
13
Geef getal 1: 
10
Geef getal 2: 
29
Geef getal 3: 
73
Geef getal 4: 
94
Geef getal 5: 
7
Geef getal 6: 
85
Geef getal 7: 
15
Geef getal 8: 
61
Geef getal 9: 
38
Getal 0: 13
Getal 1: 10
Getal 2: 29
Getal 3: 73
Getal 4: 94
Getal 5: 7
Getal 6: 85
Getal 7: 15
Getal 8: 61
Getal 9: 38
```

**Input:**

```
13
10
29
73
94
7
85
15
61
38
```

**Expected Output:**

```
Getal 0: 13
Getal 1: 10
Getal 2: 29
Getal 3: 73
Getal 4: 94
Getal 5: 7
Getal 6: 85
Getal 7: 15
Getal 8: 61
Getal 9: 38
```

---

### Case 8

**Complete console output:**

```
Geef getal 0: 
58
Geef getal 1: 
22
Geef getal 2: 
93
Geef getal 3: 
93
Geef getal 4: 
67
Geef getal 5: 
93
Geef getal 6: 
11
Geef getal 7: 
16
Geef getal 8: 
38
Geef getal 9: 
27
Getal 0: 58
Getal 1: 22
Getal 2: 93
Getal 3: 93
Getal 4: 67
Getal 5: 93
Getal 6: 11
Getal 7: 16
Getal 8: 38
Getal 9: 27
```

**Input:**

```
58
22
93
93
67
93
11
16
38
27
```

**Expected Output:**

```
Getal 0: 58
Getal 1: 22
Getal 2: 93
Getal 3: 93
Getal 4: 67
Getal 5: 93
Getal 6: 11
Getal 7: 16
Getal 8: 38
Getal 9: 27
```

---

### Case 9

**Complete console output:**

```
Geef getal 0: 
60
Geef getal 1: 
3
Geef getal 2: 
47
Geef getal 3: 
95
Geef getal 4: 
94
Geef getal 5: 
45
Geef getal 6: 
7
Geef getal 7: 
39
Geef getal 8: 
84
Geef getal 9: 
51
Getal 0: 60
Getal 1: 3
Getal 2: 47
Getal 3: 95
Getal 4: 94
Getal 5: 45
Getal 6: 7
Getal 7: 39
Getal 8: 84
Getal 9: 51
```

**Input:**

```
60
3
47
95
94
45
7
39
84
51
```

**Expected Output:**

```
Getal 0: 60
Getal 1: 3
Getal 2: 47
Getal 3: 95
Getal 4: 94
Getal 5: 45
Getal 6: 7
Getal 7: 39
Getal 8: 84
Getal 9: 51
```

---

### Case 10

**Complete console output:**

```
Geef getal 0: 
86
Geef getal 1: 
66
Geef getal 2: 
15
Geef getal 3: 
46
Geef getal 4: 
91
Geef getal 5: 
29
Geef getal 6: 
64
Geef getal 7: 
56
Geef getal 8: 
77
Geef getal 9: 
33
Getal 0: 86
Getal 1: 66
Getal 2: 15
Getal 3: 46
Getal 4: 91
Getal 5: 29
Getal 6: 64
Getal 7: 56
Getal 8: 77
Getal 9: 33
```

**Input:**

```
86
66
15
46
91
29
64
56
77
33
```

**Expected Output:**

```
Getal 0: 86
Getal 1: 66
Getal 2: 15
Getal 3: 46
Getal 4: 91
Getal 5: 29
Getal 6: 64
Getal 7: 56
Getal 8: 77
Getal 9: 33
```

---

### Case 11

**Complete console output:**

```
Geef getal 0: 
14
Geef getal 1: 
44
Geef getal 2: 
22
Geef getal 3: 
49
Geef getal 4: 
77
Geef getal 5: 
94
Geef getal 6: 
11
Geef getal 7: 
13
Geef getal 8: 
96
Geef getal 9: 
49
Getal 0: 14
Getal 1: 44
Getal 2: 22
Getal 3: 49
Getal 4: 77
Getal 5: 94
Getal 6: 11
Getal 7: 13
Getal 8: 96
Getal 9: 49
```

**Input:**

```
14
44
22
49
77
94
11
13
96
49
```

**Expected Output:**

```
Getal 0: 14
Getal 1: 44
Getal 2: 22
Getal 3: 49
Getal 4: 77
Getal 5: 94
Getal 6: 11
Getal 7: 13
Getal 8: 96
Getal 9: 49
```

---

### Case 12

**Complete console output:**

```
Geef getal 0: 
71
Geef getal 1: 
17
Geef getal 2: 
75
Geef getal 3: 
66
Geef getal 4: 
97
Geef getal 5: 
7
Geef getal 6: 
98
Geef getal 7: 
63
Geef getal 8: 
25
Geef getal 9: 
89
Getal 0: 71
Getal 1: 17
Getal 2: 75
Getal 3: 66
Getal 4: 97
Getal 5: 7
Getal 6: 98
Getal 7: 63
Getal 8: 25
Getal 9: 89
```

**Input:**

```
71
17
75
66
97
7
98
63
25
89
```

**Expected Output:**

```
Getal 0: 71
Getal 1: 17
Getal 2: 75
Getal 3: 66
Getal 4: 97
Getal 5: 7
Getal 6: 98
Getal 7: 63
Getal 8: 25
Getal 9: 89
```

---

### Case 13

**Complete console output:**

```
Geef getal 0: 
24
Geef getal 1: 
24
Geef getal 2: 
20
Geef getal 3: 
52
Geef getal 4: 
96
Geef getal 5: 
96
Geef getal 6: 
23
Geef getal 7: 
32
Geef getal 8: 
68
Geef getal 9: 
8
Getal 0: 24
Getal 1: 24
Getal 2: 20
Getal 3: 52
Getal 4: 96
Getal 5: 96
Getal 6: 23
Getal 7: 32
Getal 8: 68
Getal 9: 8
```

**Input:**

```
24
24
20
52
96
96
23
32
68
8
```

**Expected Output:**

```
Getal 0: 24
Getal 1: 24
Getal 2: 20
Getal 3: 52
Getal 4: 96
Getal 5: 96
Getal 6: 23
Getal 7: 32
Getal 8: 68
Getal 9: 8
```

---

### Case 14

**Complete console output:**

```
Geef getal 0: 
32
Geef getal 1: 
78
Geef getal 2: 
38
Geef getal 3: 
17
Geef getal 4: 
75
Geef getal 5: 
16
Geef getal 6: 
23
Geef getal 7: 
33
Geef getal 8: 
1
Geef getal 9: 
96
Getal 0: 32
Getal 1: 78
Getal 2: 38
Getal 3: 17
Getal 4: 75
Getal 5: 16
Getal 6: 23
Getal 7: 33
Getal 8: 1
Getal 9: 96
```

**Input:**

```
32
78
38
17
75
16
23
33
1
96
```

**Expected Output:**

```
Getal 0: 32
Getal 1: 78
Getal 2: 38
Getal 3: 17
Getal 4: 75
Getal 5: 16
Getal 6: 23
Getal 7: 33
Getal 8: 1
Getal 9: 96
```

---

### Case 15

**Complete console output:**

```
Geef getal 0: 
8
Geef getal 1: 
87
Geef getal 2: 
21
Geef getal 3: 
44
Geef getal 4: 
75
Geef getal 5: 
90
Geef getal 6: 
88
Geef getal 7: 
90
Geef getal 8: 
66
Geef getal 9: 
29
Getal 0: 8
Getal 1: 87
Getal 2: 21
Getal 3: 44
Getal 4: 75
Getal 5: 90
Getal 6: 88
Getal 7: 90
Getal 8: 66
Getal 9: 29
```

**Input:**

```
8
87
21
44
75
90
88
90
66
29
```

**Expected Output:**

```
Getal 0: 8
Getal 1: 87
Getal 2: 21
Getal 3: 44
Getal 4: 75
Getal 5: 90
Getal 6: 88
Getal 7: 90
Getal 8: 66
Getal 9: 29
```

---
