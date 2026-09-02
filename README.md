a=int(input("Enter a number"))
b=int(input("Enter a number"))
c=int(input("Enter a number")) 
if(a>=b and a>=c):
  if(a*a==b*b+c*c):
     print("It is a right angled triangle .The hypotenuse is",a) 
if(b>=a and b>=c):
  if(b*b==a*a+c*c):
      print("It is a right angled triangle. The hypotenuse is",b) 
if(c>=a and c>=b):
  if(c*c==a*a+b*b):
    print("It is a right angled triangle. The hypotenuse is",c)
else:
  print("Not a right angled triangle ")
