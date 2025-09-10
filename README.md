# calculator

"""
function function_name(args) {
    statements...
}
"""

"""
def function_name(args);
   statements...
"""
def add(a,b):
    return a+b
    
print(add(10,10))

def sub(a,b):
    return a-b

# print(add(10,10))
# print(add(50,50))

print(sub(72,20))

def mul(a,b):
    return a*b
    
print(mul(7,9))

def div(a,b):
    return a/b
    
print(div(9,3))

def mod(a,b):
    return a%b
    
print(mod(5,6))

operation=input("provide operation")
num1=int(input("enter number 1:"))
num2=int(input("enter number 2:"))

if operation== "+":
    print(add(num1,num2))
elif operation=="-":
    print(sub(num1,num2))
    
if operation=="*":
    print(mul(num1,num2))
elif operation=="/":
    print(div(num1,num2))
else:
    print("invalid operation")
