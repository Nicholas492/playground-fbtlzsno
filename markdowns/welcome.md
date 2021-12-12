import random
randomNumber=random.randint(10, 20)
print(randomNumber)
a=int(input("enter your random number"))
b=int(input("enter your user number"))
if a==b:
  print("this is a lottery number")
else:
  print("this is not a lottery number")