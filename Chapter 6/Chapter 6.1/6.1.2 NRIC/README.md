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

S or T:
0-j
1-Z
2-I
3-H
4-G
5-F
6-E
7-D
8-C
9-B
10-A

F or G:
0-X
1-W
2-U
3-T
4-R
5-Q
6-P
7-N
8-M
9-L
10-K
