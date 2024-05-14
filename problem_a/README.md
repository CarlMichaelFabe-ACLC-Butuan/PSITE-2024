# Problem A: Tag Content Extractor

In a tag-based language like _XML_ or _HTML_, contents are enclosed between a _start tag_ and an _end tag_ like `<tag>contents</tag>`. Note that the corresponding _end_ tag starts with a /.

Given a string of text in a tag-based language, parse this text and retrieve the contents enclosed within sequences of well-organized tags meeting the following criterion:

1. The name of the _start_ and _end_ tags must be same. The HTML code `<h1>Hello World</h2>` is _not valid_, because the text starts with an `h1` tag and ends with a non-matching `h2` tag.
2. Tags can be nested, but content between nested tags is considered _not valid_. For example, in `<h1><a>contents</a>invalid</h1>`, `contents` is _valid_ but `invalid` is _not valid_.
3. Tags can consist of any printable characters.

## Input Format

The first line of input contains a single integer, (the number of lines).\
The subsequent lines each contain a line of text.

## Constraints

- Each line contains a maximum of printable characters.
- The total number of characters in all test cases will not exceed .

## Output Format

For each line, print the content enclosed within valid tags.\
If a line contains multiple instances of valid content, print out each instance of valid content on a new line; if no valid content is found, print `None`.

## Sample Input

```
4
<h1>Nayeem loves counseling</h1>
<h1><h1>Sanjay has no watch</h1></h1><par>So wait for a while</par>
<Amee>safat codes like a ninja</amee>
<SA premium>Imtiaz has a secret crush</SA premium>
```

## Sample Output

```
Nayeem loves counseling
Sanjay has no watch So wait for a while
None
Imtiaz has a secret crush
```
