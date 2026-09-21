# Assignment-2
LCA1
def largest(a,b,c)
if a>=b and a>=c:
    return a
elif b>=a and b>=c:
    return b
else :
    return c
A=float(input("Enter first number :"))
B=float(input("Enter second number :"))
C=float(input("Enter third number :"))
find=largest(A,B,C)
print("The largest number is : {find}")