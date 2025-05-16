# functions
code--1::
#fuction caling and defining
def hi():
    print("Good afternoon ")
hi()
output::
Good afternoon 

cde--2:
#function with parameters
def hi(name):
    print("Hello",name)
hi('Vijay')

output::
Hello Vijay

code--3::
#function return values
def add(a,b):
    return a+b
x=int(input("enter the value of x:"))
y=int(input("enter th value of :"))
result=add(x,y)
print("sum",result)

output::
enter the value of x: 5
enter th value of : 10
sum 15

code--4;
#default paramaters/func occupied parameters
def hi(name='Sinchan'):
    print("Hello",name)
hi()
hi("Doremon")
output::
Hello Sinchan
Hello Doremon

code--5
'''write a fuction that carries and return all the arthmetic operations
to the main code(+,-,*)
pass the constraints,where all the constrints must be caliculated 
accordigly as return values to print  by calling the same function
'''
def ao(x,y):
    return x+y,x-y,x*y
x=int(input("enter a values:"))
y=int(input("enter a another values:"))
tot,diff,prod=ao(x,y)
print("sum:",tot)
print("sub:",diff)
print("mul:",prod)

output::
enter a values: 10
enter a another values: 5
sum: 15
sub: 5
mul: 50
