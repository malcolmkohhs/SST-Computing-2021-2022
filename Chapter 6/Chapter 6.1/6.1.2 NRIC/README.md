Write a program to ask the user for an NRIC input.
It consist of a alphabet prefix, 7 digits and an alphabet check digit.
Validate the input, allow user to re-enter if validation fails.
Using the following algorithm, determine if the check digit is correct.
Multiply each digits with the following weightage, [2, 7, 6, 5, 4, 3, 2]
i.e. 1st digit * 2, 2nd digit * 7, etc
Sum up the 7 values from the multiplication
If the alphabet prefix is 'T' or 'G', add 4 to the total sum.
Continue next slide

Divide total sum by 11 and get the remainder.
Use the table below, cross reference the remainder with the prefix to determine the check digit.

|      | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|------|---|---|---|---|---|---|---|---|---|---|----|
|S or T| J | Z | I | H | G | F | E | D | C | B | A  |
|F or G| X | W | U | T | R | Q | P | N | M | L | K  |
