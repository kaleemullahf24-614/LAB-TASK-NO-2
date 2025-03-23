# LAB-TASK-NO-2:
# EXCRISE NO 1:
def hello_name(name):
    print("Hello, " + name + "!")

# Example usage:
hello_name("Ali")
# OUTPUT:
Hello, Ali!

# EXCRISE NO 2:
def calculate_area(length, width=10):
    return length * width

# Example usage:
print(calculate_area(5))  # Output: 50 (using default width of 10)
print(calculate_area(5, 20))  # Output: 100 (using custom width of 20)
# OUTPUT:
50
100

# EXCRISE NO 3:
def is_even(num):
    return num % 2 == 0

# Example usage:
print(is_even(10))  # Output: True
print(is_even(11))  # Output: False
# OUTPUT:
True
False

# EXCRISE NO 4:
x = 10  # global variable

def modify_global():
    global x  # declare x as global
    x = 20  # modify the global variable
    print("Inside function:", x)

modify_global()
print("Outside function:", x)
# OUTPUT:
Inside function: 20
Outside function: 20

# EXCRISE NO 7:
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def operate(func, a, b):
    return func(a, b)

# Example usage:
print(operate(add, 10, 5))      # Output: 15 (10 + 5)
print(operate(subtract, 10, 5)) # Output: 5 (10 - 5)
print(operate(multiply, 10, 5)) # Output: 50 (10 * 5)
# OUTPUT:
15
5
50
