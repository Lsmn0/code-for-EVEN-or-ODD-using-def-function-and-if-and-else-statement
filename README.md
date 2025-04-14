# code-for-EVEN-or-ODD-using-def-function-and-if-and-else-statement
code for EVEN or ODD using def function and if and else statement
n = int(input("enter the number: "))
def even(n):
    if n < 0:
        print("Negative number")
        
    elif n == 0:
        print("Number cannot be zero")

    else:
        if n % 2 == 0:
            print("EVEN")
        else:
            print("ODD")
even(n)

    
