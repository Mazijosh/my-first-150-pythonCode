#!/bin/python3

#print string
print ("strings and things:")
print ('Hello world!')
print ("""Hello, this is 
amulti-line string!""")
print ("This is "+" a string")

print('\n') #new line

#MathS
print ("Math time:")
print (50 + 50) #add
print (50 - 50) #subtract
print (50 * 50) #multiply
print (50 / 50) #divide
print (50 + 50 * 50 / 50) #PEMDAS
print (50 ** 2) #exponents
print (50 % 6) #modulo
print (50 // 6) #number without leftovers

print('\n') #new line

#Variables & Methods
print ("Fun with variables and methods:")
quote = "Life is for the living"
print (len(quote)) #length
print (quote.upper()) #uppercase
print (quote.lower()) #lowercase
print (quote.title()) #title

name = "Josh"
age = 47 #int int(47)
gra = 4.10 #float float(4.10)

print (int(age))
print (int(47.7)) #does not round

print("My name is " + name + " and im " + str(age) + " years old.")

print('\n') #new line

age += 3
print(age)

birthday = 1
age += birthday
print(age)

print('\n') #new line

#Functions
print("Now, some functions:")
def who_am_i():
        name = "Josh"
        age = 47
        print("My name is " + name + " and im " + str(age) + " years old.")

who_am_i()

#adding in parameters
def add_one_hundred(num):
        print(num + 100)
        
add_one_hundred(100)

#add in multiple parameters
def add(x,y):
        print (x + y)
        
add(7,7)
add(305,207)

#using return
def multiply(x,y):
        return x * y
        
print(multiply(7,7))

def square_root(x):
       return x ** .5
       
print(square_root(64))

print('\n') #new line

#Boolean Expressions (True or False)
print("Boolean expressions:")
bool1 = True
bool2 = 3*3 == 9
bool3 = False
bool4 = 3*3 != 9

print(bool1,bool2,bool3,bool4)
print(type(bool1))

bool5 = "True"
print(type(bool5))

#Relational and Boolean Operators
greater_than = 7 > 5
less_than = 5 < 7
greater_than_equal_to = 7 >= 7
less_than_equal_to =7 <= 7

print(greater_than,less_than,greater_than_equal_to,less_than_equal_to)

test_and = (7 > 5) and (6 <7)
test_or = (7 > 5) or (5 <7)
test_not = not True

print(test_and)

print('\n') #new line

#Conditional statements
print("Conditional statements:")

def soda(money):
       if money >=2:
           return "You've got yourself a soda!"
       else:
           return "No soda for you today!"
           
print(soda(3))
print(soda(1))

def Alcohol(age,money):
        if (age >= 21) and (money >= 5):
            return "Its tipsy day for you lad!"
        elif (age>= 21) and (money < 5):
            return "Bro, you're borke. No beer for you."
        elif (age < 21) and (money >= 5):
            return "You're too young to drink, come back when 18+"
        else:
            return "You're too young and broke"
            
print(Alcohol(21,5))
print(Alcohol(21,4))
print(Alcohol(20,4))

