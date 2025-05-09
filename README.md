#swapping with temporary variable
a= int(input("Enter the value of a :"))
b= int(input("Enter the value of b :"))
print("Before swap",a,b)
temp= a
a= b
b= temp
print("after swap", a,b)
