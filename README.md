# AmirHossein-Hadi-first-project
# شروع سریع پایتون
print("Hello, World!")

# اجرای مستقیم در خط فرمان
print("Hello, World!")

# تورفتگی در پایتون
if 5 > 2:
    print("Five is greater than two!")

# متغیرها
x = 5
y = "Hello, World!"
print(x)
print(y)

# کامنت‌ها
# This is a comment.
print("Hello, World!")

print("Hello, World!")  # This is a comment

# چند خطی
# This is a comment
# written in
# more than just one line
print("Hello, World!")

"""
This is a comment
written in
more than just one line
"""
print("Hello, World!")

# نوع داده متغیرها
x = 5
y = "John"
print(x)
print(y)

x = 4       # int
x = "Sally" # str
print(x)

# Casting
x = str(3)   # '3'
y = int(3)   # 3
z = float(3) # 3.0
print(x)
print(y)
print(z)

# نوع متغیر
x = 5
y = "John"
print(type(x))
print(type(y))

# نقل قول تکی و دوتایی
x = "John"
x = 'John'

# حساسیت به حروف بزرگ و کوچک
a = 4
A = "Sally"
print(a)
print(A)

# نام‌گذاری متغیرها
myvar = "John"
my_var = "John"
_my_var = "John"
myVar = "John"
MYVAR = "John"
myvar2 = "John"

# نام‌های چند کلمه‌ای
myVariableName = "John"   # Camel Case
MyVariableName = "John"   # Pascal Case
my_variable_name = "John" # Snake Case

# چند مقدار در یک خط
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)

# یک مقدار برای چند متغیر
x = y = z = "Orange"
print(x)
print(y)
print(z)

# باز کردن مجموعه (unpacking)
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)

# خروجی متغیرها
x = "Python"
y = "is"
z = "awesome"
print(x, y, z)

x = "Python is awesome"
print(x)

x = "Python "
y = "is "
z = "awesome"
print(x + y + z)

# جمع اعداد
x = 5
y = 10
print(x + y)

# رشته و عدد
x = 5
y = "John"
print(x, y)

# متغیر سراسری
x = "awesome"

def myfunc():
    print("Python is " + x)

myfunc()

# متغیر محلی
x = "awesome"

def myfunc():
    x = "fantastic"
    print("Python is " + x)

myfunc()
print("Python is " + x)

# تغییر متغیر سراسری با global
x = "awesome"

def myfunc():
    global x
    x = "fantastic"

myfunc()
print("Python is " + x)
