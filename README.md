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
