In cryptography, a Caesar cipher, or shift cipher, is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet. For example, with a shift of 3, A would be replaced by D, B would become E, and so on. 

Your task is to write a function caesar(plaintext, a, b) to implement a modified Caesar cipher with 2 shift numbers, "a" and "b", on the plaintext. “a” and “b” are integers between 0 and 25 inclusive. 

Your program should:
1) Read in the plaintext, a string, which may include punctuation, numbers, and upper and lower case letters.
2) Starting from 0, for each character in the string, 
    a) if the character is alphabetical and its position in the string is ODD, shift it by the first shift number "a",
    b) if the character is alphabetical and its position in the string is EVEN, shift it by the second shift number "b",
    c) if the character is NOT alphabetical, do nothing to it and copy it into the ciphertext.
3) Print out the ciphertext.

** Incremental decomposition (simplification): For a start, you may want to focus only on uppercase letters, before adding in lower case.
** Incremental decomposition (complication): If you are done with the task above, consider how to implement a left shift, meaning a shift of some fixed number of positions up the alphabet. For example, with a shift of -3, D would be replaced by A.


Then:
1) Write a gibberish string (a string with no meaningful words) that contains the word "duck" (in either upper or lower case, or mix). 
2) Post your ciphertext here for others to decode! 
3) Then try to crack your friends' ciphertexts. If you are successful, be the first to post the shift numbers "a" and "b" as a reply to their post.