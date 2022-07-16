Task: AddSum 

AddSum is a function defined as:
AddSum(0, n) = n, for all positive n.
AddSum(k, n) = AddSum(k-1, 1) + AddSum(k-1, 2) + … + AddSum(k-1, n), for all positive k, n.


Write a function with the following method signature:   def AddSum(k, n):

Given k and n, where 1≤ k, n ≤ 14, output the value of AddSum(k, n)

Examples 1:        
1 3
Returns: 6
When k = 1, AddSum is equal to the sum of the first n = 3 numbers: 1 + 2 + 3 = 6.


Example 2:        
2 3
Returns: 10

Submit class_index_addsum.py where class ∈ {401, 402, 407} and index is a two-digits number (leading zero if necessary).

Test Data
1) (2,3) → 10
2) (7,10) → 24310
3) (14,14) → 37442160


RP Result Timing for (14,14)
Normal           37442160    Time:7.6217920780181885
Memoisation 37442160    Time:0.0005781650543212891
Tabulation.     37442160    Time:5.5789947509765625e-05