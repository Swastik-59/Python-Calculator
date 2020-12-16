# Python-Calculator-
This is a simple CALCULATOR made with Python.
# PYTHON CALCULATOR

# First create functions of Add,Subtract,Multiply,Divide
def add(num1, num2):
    return num1+num2


def subtract(num1, num2):
    return num1-num2


def multiply(num1, num2):
    return num1*num2


def divide(num1, num2):
    return num1/num2

# Print the oprations 
print("please select operations -\n"
      "1. Add\n"
      "2. Subtract\n"
      "3. Multiply\n"
      "4. Divide\n")

# Take input from user to choose the oprations to do
select = int(input("select operations form 1,2,3,4 :"))

# Take input of numbers from user 
number_1 = int(input("Enter first number :"))
number_2 = int(input("Enter second number :"))

# For Repeating the program
while True:

    # If selected 1        (1 is for Adding)
    if select == 1:
        print(number_1, "+", number_2, "=",
              add(number_1, number_2))

    # If selected 2        (2 is for Subtracting)
    elif select == 2:
        print(number_1, "-", number_2, "=",
              subtract(number_1, number_2))

    # If selected 3        (3 is for Multiplying)
    elif select == 3:
        print(number_1, "*", number_2, "=",
              multiply(number_1, number_2))

    # If selected 4        (4 is for Dividing)
    elif select == 4:
        print(number_1, "/", number_2, "=",
              divide(number_1, number_2))

    # For exception 
    else:
        print("invalid input")

    # Take input from user to choose the oprations to do
    select = int(input("select operations form 1,2,3,4 :"))

    # Take input of numbers from user 
    number_1 = int(input("Enter first number :"))
    number_2 = int(input("Enter second number :"))
