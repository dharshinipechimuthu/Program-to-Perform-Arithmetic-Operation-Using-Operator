# Program-to-Perform-Arithmetic-Operation-Using-Operator
a = int(input("Enter 1st number: "))
b = int(input("Enter 2nd number: "))
c = input("Enter the Operation (+,-,/,*): ")

if c == '+':
    print("The result is", a + b)
elif c == '-':
    print("The result is", a - b)
elif c == '/':
    print("The result is", a / b)
elif c == '*':
    print("The result is", a * b)
else:
    print("Error: Wrong operator entered")

Output:
Enter 1st number: 10
Enter 2nd number: 5
Enter the Operation (+,-,/,*): *
The result is 50
