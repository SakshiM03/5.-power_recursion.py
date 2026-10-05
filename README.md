# 5.-power_recursion.py
def power(base, exponent):
    # Base case
    if exponent == 0:
        return 1

    # Recursive case
    return base * power(base, exponent - 1)


base = 2
exponent = 5

result = power(base, exponent)

print(base, "^", exponent, "=", result)

Output:

2 ^ 5 = 32
