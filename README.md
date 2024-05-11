Hello everyone just testing this.

# This is a simple open-source project code to calculate factorial using recursion

def factorial(n):
    """Function to calculate factorial of a number using recursion."""
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

if __name__ == "__main__":
    # Taking user input for the number
    num = int(input("Enter a non-negative integer: "))

    # Checking if the number is non-negative
    if num < 0:
        print("Factorial is not defined for negative numbers.")
    else:
        result = factorial(num)
        print(f"The factorial of {num} is {result}.")

