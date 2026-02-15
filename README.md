def calculate_gcd(a, b):
    while b:
        a, b = b, a % b
    return a

if __name__ == "__main__":
    x = 48
    y = 18
    print(f"GCD of {x} and {y} is {calculate_gcd(x, y)}")
