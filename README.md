def fact(n):
    if n == 0:
        return 1
    else:
        return n * fact(n-1)
result=fact(5)
print("Factorial of  5 is:",result)

##  task2
import math
a=int(input("Enter the number"))
print( "square root:",math.sqrt(a))
print("logarithm:",math.log(a,2))
print("sine:",math.sin(a))
