
# Python Assignment



![Logo](https://i0.wp.com/junilearning.com/wp-content/uploads/2020/06/python-programming-language.webp?fit=800%2C800&ssl=1)

Assignment:

Question: Printing prime number

n = 11

c = 0

for i in range(1, n+1):

  if n % i == 0:
    c = c + 1

if c == 2:

  print(f'{n} Is a prime number')

else:
  print(f'{n} Not a Prime number')


 Output: 11 Is a prime number.

 ## 

 # I want to print the prime number from 1 to 100

for n in range(1,101):
  c = 0

  for i in range(1,n+1):

    if n % i == 0:
      c = c + 1


  if c == 2:
   print(n)

   Output:
   2
3
5
7
11
13
17
19
23
29
31
37
41
43
47
53
59
61
67
71
73
79
83
89
97
