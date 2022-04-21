# factorial-of-a-number

def factorial(num):
if(num==1 or num==0):
return 1
else:
return num*factorial (num-1)

n=int(input())
print("factorial of",n,"is",factorial (n))
