# Calculator
def add(a,b):
    add=a+b
    print('addition is',add)

def sub(a,b):
    sub=a-b
    print('sub is',sub)

def mul(a,b):
    mul=a*b
    print('mul is',mul)

def div(a,b):
    div=a/b
    print('div is',div)

a=int(input("enter a:"))
b=int(input("enter b:"))
 
print("select operation")
print("add is 1")
print("sub is 2")
print("mul is 3")
print("div is 4")
choice=int(input("enter your choice:"))
if (choice==1):
        add(a,b)
elif(choice==2):
        sub(a,b)
elif(choice==3):
        mul(a,b)
elif(choice==4):
        div(a,b)  
else :
    print ("invalid input")
    




