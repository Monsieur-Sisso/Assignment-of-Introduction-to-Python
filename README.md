# Assignment-of-Introduction-to-Python



def calculator():
    try:
        num1 = float(input("Enter the first number: "))
        num2 = float(input("Enter the second number: "))

        operation = input("Enter a mathematical operation (+, -, *, /): ")

        if operation == "+":
            result = num1 + num2
            print(f"{num1} + {num2} = {result}")
        elif operation == "-":
            result = num1 - num2
            print(f"{num1} - {num2} = {result}")
        elif operation == "*":
            result = num1 * num2
            print(f"{num1} * {num2} = {result}")
        elif operation == "/":
            if num2 != 0:
                result = num1 / num2
                print(f"{num1} / {num2} = {result}")
            else:
                print("Division by zero is not allowed.")
        else:
            print("Invalid operation. Please enter +, -, *, or /.")
    except ValueError:
        print("Invalid input. Please enter numeric values.")

calculator()
