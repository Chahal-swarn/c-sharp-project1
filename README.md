print("Welcome to Package Express. Please follow the instructions below.")

weight = float(input("Please enter the weight of your package in pounds:  "))

if weight>50:

print("package too heavy to be shipped via Package Express. Have a good day.")

else:

width = float(input("please enter the width of your package in inches: "))

height = float(input("please enter the height of your package in inches: "))

length = float(input("please enter the length of your package in inches: "))

if width+ height+ length >50:

print("package too big to be shipped via Package Express. Have a good day.")

else:

quote = (width * height * length * weight)/100

print( f" your shipping quote is: ${ quote:.2f} " )



 
