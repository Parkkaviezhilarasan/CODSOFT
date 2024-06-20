# CODSOFT
Python programming
# get the input values
number1=int(input("Enter the first number"))
number2=int(input("Enter the second number"))
# get the choice
choice=input("enter your operation symbol")
# perform hte operation using given symbol
if choice=="+":
    result=number1+number2
    print(result)
elif choice=="-":
    result=number1-number2
    print(result)
elif choice=="/" :
    result=number1/number2
    print(result)
elif choice=="*" :
    result=number1*number2
    print(result)
else:
    print("Operation not found")

