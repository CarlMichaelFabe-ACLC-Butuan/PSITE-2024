# Problem H: Time Processing with Roman Numerals

Below is the specified instruction for this problem set:

1. Implement the `is_prime(n)` function, which takes an integer `n` as input and returns `True` if `n` is a prime number, otherwise `False`.
2. Implement the `convert_to_12_hour_format(hours)` function, which takes an integer `hours` representing time in 24-hour format and converts it to 12-hour format. If the input is 0, it should return 12. If the input is greater than 12, it should subtract 12 from the input. Otherwise, it should return the input unchanged.
3. Implement the `process_time(input_file, output_file)` function, which reads time data from an input file named `input_file`, performs calculations based on the given operations, and writes the result to an output file named `output_file`. The input file contains lines of time data in Roman numeral format separated by spaces (e.g., `XXII XL XXXIII`). For each line of input, the function should convert the time to 12-hour format, add or subtract a specific number of seconds based on whether the total seconds calculated from the time is prime or not, and then write the resulting time to the output file in the format `seconds minutes hours` (e.g. `XVIII XL X`).

## Constraints

- The input file contains valid time data in Roman numeral format.
- The input time is in the range 00:00:00 to 23:59:59.

## Input

```
XXII XL XXXIII
```

# Output

```
XVIII XL X
```
