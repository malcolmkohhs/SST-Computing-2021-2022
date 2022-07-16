Given two strings, S1 and S2, output "True" if all characters in S1 appear in S2, otherwise output "False"
Positions, sequences and cases do matter. All characters found in S2 must be in consecutive order without any characters from S1 in-between

Example 0
S1: "PYv"
S2: "PYthonPositive"
Output: False
Explanation: To form PYv, the string has to go through PYPv. As the second "P" character is in S1, therefore output is False.

Example 1
S1: "Pov"
S2: "PYthonPositive"
Output: True
Explanation: From S2, you should get PoPov, since the last three characters matches S1 without any other valid characters in S1,  output is True
