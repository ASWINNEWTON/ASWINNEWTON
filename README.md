- 👋 Hi, I’m @ASWINNEWTON
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ASWINNEWTON/ASWINNEWTON is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
num1 = 10
num2 = 14
num3 = 12

# uncomment following lines to take three numbers from user
#num1 = float(input("Enter first number: "))
#num2 = float(input("Enter second number: "))
#num3 = float(input("Enter third number: "))

if (num1 >= num2) and (num1 >= num3):
   largest = num1
elif (num2 >= num1) and (num2 >= num3):
   largest = num2
else:
   largest = num3

print("The largest number is", largest)


# taking input from user
num1 = float(input("Enter 1st number: "))
num2 = float(input("Enter 2nd number: "))
num3 = float(input("Enter 3rd number: "))

if (num1 >= num2) and (num1 >= num3):
   lnum = num1
elif (num2 >= num1) and (num2 >= num3):
   lnum = num2
else:
   lnum = num3

print("The largest number among",num1,",",num2,"and",num3,"is: ",lnum)
