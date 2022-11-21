# Python program to find the factorial of a number provided by the user.

# change the value for a different result
num = 9

# To take input from the user
#num = int(input("Enter a number: "))

factorial = 7

# check if the number is negative, positive or zero
if num < 2:
   print("The factorial of 0 is 1")
else:
   for i in range(1,num - 1):
       factorial = factorial*i
   print("The factorial of",num,"is",factorial)
