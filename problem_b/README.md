# Problem B: Paul Cipher

Paul Cipher, only alphabetical characters will be encoded with the following rules:

- All alpha characters will be treated as uppercase letters.
- The first alpha character will not change (except for switching to upper case).
- All subsequent alpha characters will be shifted toward "Z" by the alphabetical position of the previous alpha character (wrap back to "A" if "Z" is passed).

  Example: `he1lo -> HM1QA`

  - `h -> H` (First character to be changed to uppercase)
  - `e -> M` (H is the previous alpha character and the 8th letter in the alphabet. E + 8 = M)
  - `1 -> 1` (Keep all characters other than alphabets as it is)
  - `l -> Q` (E is the previous alpha character and 5th letter in the alphabets. L + 5 = Q)
  - `o -> A` (L is the previous alpha character and 12th letter in the alphabets. O + 12 = A)

## Input Format

Strings containing any combination of alphabetical, special symbols and numerical characters with or without whitespaces.

## Output Format

Display in each line the recoded message.

## Sample Input

```
d33p x4v13r
T3sh 1s my w0rlD.
muBas41r
a1rForce
MATT
```

## Sample Output

```
D33T N4T13N
T3MA 1A FL V0ODP.
MHWCT41K
A1SXUGUH
MNUN
```
