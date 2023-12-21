# python-calculator
first=int(input("Enter first digit="))
operator=input("Enter any operator....+,-,*,/,%,**")
second=int(input("enter second number"))
if operator=="+":
    print(first+second)
elif operator=="-":
    print(first-second)
elif operator=="*":
    print(first*second)
elif operator=="/":
    print(first/second)
elif operator=="%":
    print(first%second)
elif operator=="**":
    print(first**second)
else:
    print("you perform invalid statement")
print("thank you")
