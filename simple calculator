def calculate(x, y, ch):
    if ch >= 1 and ch <= 4:
        if ch == 1:
            return (f"{x} + {y} = {x+y}")
        elif ch == 2:
            return (f"{x} - {y} = {x-y}")
        elif ch == 3:
            return (f"{x} * {y} = {x*y}")
        elif ch == 4:
            return (f"{x} / {y} = {x/y}")
    else:
        return ("WRONG OPERATION INDEX")

while True:
    ch = int(input("""
[1] Addition
[2] Subtraction
[3] Multiplication
[4] Division
        
Choose an operation to perform [1-4]: """))

    x = float(input("Enter the value of x: "))
    y = float(input("Enter the value of y: "))

    print(f"Answer: {calculate(x, y, ch)}")
