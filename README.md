# Fibonacci
#printing Fibonacci series

a=0
b=1
n=int(input("Write number of terms you want to print "))
i=0
if n<=0:
  print("Write a positive integer")
elif n==1:
  print(a)
else:
  for i in range(n):
    print(a)
    c=a+b
    a=b
    b=c
    i+=1
 
 
