# hw16

a= int(input("enter number for a: "))

c= int(input("enter number for c: "))

b=int(input("enter number for b: "))

delta= b**2 - (4* a)*c

if a==0:
    print(" not a quadratic, cant be zero")
elif delta> 0:
    rootsneg = (-b -delta**0.5)/(2*a)
    rootspos= (-b + delta**0.5)/(2*a)
    print(" the roots are", rootspos, rootsneg )
elif delta==0:
    print ("the root is ", (-b)/(2*a))
elif delta <0 :
    print (" there are no real roots")

else:
    print (" somethings wrong")
    
