Sum of decimals that are binary representations of first N natural numbers
Examples:

Input: N = 3
Output: 22
Explanation:
The Binary Representation of 1 is 01.
The Binary Representation of 2 is 10.
The Binary Representation of 3 is 11.
Therefore, required sum = 01 + 10 + 11 = 22.

Input: N = 5
Output: 223
#PYTHON
l=[]
def func(n):
   return bin(int(n)).replace("0b", "")
n=int(input())
for i in range (1,n+1):
   l.append(int(func((i))))
print(l)   
print("Sum of decimals that are binary representation of first N natural numbers:" ,sum(l))
