Project Name: replace.py

1. # What It Does

a. Original String
Prints the original string:
"The!quick!brown!fox!jumps!over!the!lazy!dog."

b. Replace Exclamation Marks
Replaces all ! with spaces and prints:
"The quick brown fox jumps over the lazy dog."

c. Convert to Uppercase
Converts the string to uppercase:
"THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG."

d. Reverse the String 
Reverses the uppercase string and prints:
".GOD YZAL EHT REVO SPMUJ XOF NWORB KCIUQ EHT"

2. # String Manipulation in Python

This simple Python script demonstrates basic string manipulation techniques including replacing characters, converting to uppercase, and reversing a string.

a. # Code Overview

``` Python

quote = "The!quick!brown!fox!jumps!over!the!lazy!dog."
print(quote)

quote_replace = quote.replace("!", " ")
print(quote_replace)

quote_upper = quote_replace.upper()
print(quote_upper)

print(quote_upper[::-1])
