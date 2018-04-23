def add(num1, num2):
    return (num1 + num2)

def sub(num1,num2):
    return (num1 - num2)

def mul(num1, num2):
    return (num1 * num2)

def div(num1, num2):
    return (num1 / num2)

num1 = input ("Number 1: ")
num2 = input ("Number 2: ")
operation = input ("Operation: ")

 if operation == "add":
          print(add(num1,  num2))

    elif operation == "sub":
          print(sub(num1, num2))

    elif operation == "mul":
          print(mul(num1, num2))

    elif operation == "div":
          print(div(num1,  num2))
          
print operation
