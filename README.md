
# Python Assignment

Question:Printing prime number

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


# Question: 1

# a = [[1,2], [3,[4,5]],[6]]

# Sample output = [1,2,3,4,5,6]

a = [[1,2],[3,[4,5]],[6]]

temp = []

for i in a: # here "i" will pick [1,2], [3,[4,5]],[6]
   
   for j in i: # here "j" will pick 1,2,3,[4,5],6
     
     if type(j) == list:

        for k in j: # here "k" will pick 4,5

            temp.append(k)

     else:
             temp.append(j)  

print(temp)
  

Output: [1, 2, 3, 4, 5, 6]
