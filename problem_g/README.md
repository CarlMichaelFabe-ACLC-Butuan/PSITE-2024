# Problem G: Word Analysis and Manipulation

You are given a string of text. Your task is to analyze the text and perform various operations based on the given instructions.

## Input

A string of text consisting of words separated by spaces.

## Output

1. Word Count: Display each unique word in the input text along with its frequency count.
2. Top 5 Words: Display the top 5 most frequently occurring words along with their counts.
3. Text with `old_word` replaced by `new_word`: Replace a specified word with another specified word and display the modified text.
4. Text Statistics: Display statistics about the input text including total number of words, total number of unique words, average word length, longest word, and shortest word.

## Sample Input

```
There is much wood would a woodchuck chuck if a woodchuck could chuck wood
```

## Sample output

```
Word Count:
there: 1
is: 1
much: 1
wood: 2
would: 1
a: 2
woodchuck: 2
chuck: 2
if: 1
could: 1

Top 5 Words:
wood: 2
a: 2
woodchuck: 2
chuck: 2
there: 1

Text with 'old_word' replaced by 'new_word':
There is much wood would a woodchuck chuck if a woodchuck could chuck wood

Text Statistics:
Total number of words: 14
Total number of unique words: 10
Average word length: 4.36
Longest word: woodchuck
Shortest word: a
```
