***Interview Question***
1. What is the output of this code?
   ```python
   s= "abjadhjsdj'
   s[-3] =?
**Ans:** 's'

2. Write a code for prime and non-prime number?
**Code: **
```python
num = 7
"""consider flag = 0 is indicating prime"""
flag = 0
if (num ==1 or num ==2):
  flag = 0
else:
  for i in range(2, num):
     if num%i ==0:
         flag = 1
     else:
         flag = 0
     print(i, flag," ", num%i)
     if flag == 1:
         break;

if flag == 1:
    print("non-prime")
else:
    print("prime")


   
