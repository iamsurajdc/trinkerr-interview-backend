# Trinkerr Backend Interview

## Back to School
Suppose you are given 2 strings which will include digits from 0-9 and the string can be of any length. You need to add those 2 strings as `numbers` and return the output as string. You need to do this as efficiently as possible. Again emphasizing on the point that the string can be of any length.

`Example-1`

```
str1 = "123456"
str2 = "312321"

output = "435777"
```

`Example-2`

```
str1 = "123456"
str2 = "123456"

output = "246912"
```
---

## Eliminating the Unwants
Suppose you are give 2 strings, one the `input` and the other one as the `unwant`. 

You need to find the occurence of the `unwant` string and remove it from the input. You need to basically remove all the `unwant` string occurences from the input.

`Example-1`

input = "daabcbaabcbc", unwant = "abc"

Output: "dab"

Explanation: The following operations are done:
- input = "daabcbaabcbc", remove "abc" starting at index 2, so input = "dabaabcbc".
- input = "dabaabcbc", remove "abc" starting at index 4, input  = "dababc".
- input = "dababc", remove "abc" starting at index 3, so input = "dab".
Now s has no occurrences of "abc".


`Example-2`

input = "axxxxyyyyb", unwant = "xy"

Output: "ab"

Explanation: The following operations are done:
- input = "axxxxyyyyb", remove "xy" starting at index 4 so input = "axxxyyyb".
- input = "axxxyyyb", remove "xy" starting at index 3 so input = "axxyyb".
- input = "axxyyb", remove "xy" starting at index 2 so input = "axyb".
- input = "axyb", remove "xy" starting at index 1 so input = "ab".

Now input has no occurrences of "xy".
