#program to convert kilometer to miles using if else
kilometer=float(input())
c=0.621371
if kilometer in range(0,70):
    miles=kilometer*c
    print(miles)
else:
    miles=kilometer*c
    print(miles,"after 70")

    #progarm to solve quadratic equation
import math
a=float(input())
b=float(input())
c=float(input())
#to check the discriminant
d=b**2-4*a*c
#roots are real and distinct
if d>=0:
    root1=(-b+math.sqrt(d))/2*a
    root2=(-b-math.sqrt(d))/2*a
    print(root1)
    print(root2)
#roots are equal
elif d==0:
    root=-b/2*a
    imaginary=math.sqrt(abs(d))/(2*a)
    print(f"{root} + {imaginary}")
    print(f"{root} - {imaginary}")
else:
    root4=-b/2*a
    print(root4)
    
#program to print is it positive ,negative,zero
num=int(input())
if num>0:
    print("positive")
elif num<0:
    print("negative")
else:
    print("zero")
