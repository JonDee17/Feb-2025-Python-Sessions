 Basic Calculator Program
# Taking user input
num1 = 9
num2 = 18
operation = '*'

# Performing the operation
if operation == '+':
    result = num1 + num2
elif operation == '-':
    result = num1 - num2
elif operation == '*':
    result = num1 * num2
elif operation == '/':
    if num2 != 0:
        result = num1 / num2

# Displaying the result
print(f"{num1} {operation} {num2} = {result}")
