def greet():
    print("  крестики-нолики  ")
    print("  формат ввода: x y")
    print(" x - номер строки  ")
    print(" y - номер столбца ")

def show():
    print()
    print("    | 0 | 1 | 2 |")
    print("   ______________")
    for i, row in enumerate(field):
        row_str = f"  {i} | {' | '.join(row)} |"
        print(row_str)
        print("  _________________")
    print()


def ask():
    while True:
        cords = input("       Ваш ход:").split()


