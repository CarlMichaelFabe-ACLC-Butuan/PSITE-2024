# Problem E: Target Indices

Given an array of integers and a target number. You should find two different items in the array that when added together will equal the target number. Return the index of these two numbers (lowest index first). The input will always be valid (numbers will be an array of length 2 or greater, and all of the items will be numbers; target will always be the sum of two different items from that array).

## Input

The first line of input is an integer `T` (`T` < 100) which is the number of array and targets to test. The next line or lines are/is a sequence of integers separated by one space. This sequence of integers are the items of the array and ends when a line that contains an asterisk is read. A newline following this asterisk is an integer that will be the target number.

## Output

For each test return the two index of the two numbers totalling the target (lower index first). See sample below for the correct format

## Sample Input

```
4
1 2 3
*
4
1234 5678 9012
*
14690
20 102 118 93 17 100 44 42 58 17 54 76 114 26 44 29 94
12 20 28 89 37 60 11 6 60 88 64 55 19 6 36 45
*
23
30 32 24 29 75 16 16 40 91 112 117 35 60 103 51 67 24
21 85 115 15 74 112 107 79 66 93 25 23 69 28 68 77 67
54 68 24 31 119 117 79 109 17 111 2 11 55 31 23 30 93
18 97 14 28 28 99 21 119 16 23 50 23 22 40 101 59 79 90
68 83 53 66 71 5 61 27 25 112 3 42 4 82 39 46 10 88 87
18 111 12 95 90
*
177
```

## Sample Output

```
0 2
1 2
17 23
10 12
```
