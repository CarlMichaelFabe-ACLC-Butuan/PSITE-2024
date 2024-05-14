# Problem F: Two Times the Charm

Given a series of numbers we are looking for those charming ones - numbers that contain at most 2 distinct digits: so these are charming numbers: `23`, `35`, `100` and `12121`. While these numbers are not charming at all: `123` and `9980`

## Input

The inputs will be a series of random positive integers _n_. This series will end with a negative number and this should not be processed.

## Output

For each input read return the next higher charming number. If _n_ itself is a charming number, return the next charming number higher than _n_

## Sample Input

```
120
1234
20
5
131
416
20
700
707
-5
```

## Sample Output

```
121
1311
21
10
133
422
21
707
711
```
