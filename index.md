# Introduction to Python's Resumes

Welcome to my Introduction to Python's Resumes at Suka Sekolah's Code Class 101.

## Week 1

In this first day we are learning the basic of computing.
Before we start coding, we need to understand some of the computation fundamentals because we'll be able to fully understand coding.

### What a Computer can do ?

We usually use computer for our daily activity like :
- Play Computer Games
- Make a Document
- Edit Photos or Videos
- Browse the Internet
- etc.

> But, Basicly Computer only be able to do 2 things
1. Store Information
2. Perform **Calculations** (Billions of calculations per second)

### What Calculations?
```
By default, the computer can perform calculations that are built-in in the programming language such as
1. Simple Arithmetic Operations
2. Comparation
3. Loop
```

As a programmer we can combine those calculations,
1. Exponent

  We Combine Addition, Substraction, Multiplication, and Division (1) with Loop (3)

2. Array

  We Combine Simple Arithmetic(1), Comparation(2), Loop(3), and Storing Information

### Knowledge
```
Computer doesn't have any knowledge like human
- Computer is just a machine to store and calculate
- Computer executes the commands given by the user.
- The "knowledge" that a computer has is limited to information and rules that are stored in memory.
- As users, we enter our knowledge into computers.
```

> Knowledge divided into 2 types
> 1. Declarative Knowledge
> 2. Imperative / Procuderal Knowledge

**Declarative Knowledge**
Declarative Knowledge = a type of knowledge in the form of a statement of a fact, so that in this type the steps to achieve a fact are not shown.
Example : "The Chair is made of wood", "My Shirt is on that bag"

**Imperative/Procuderal Knowledge**
Imperative Knowledge = a type of knowledge that shows the steps to achieve a goal.
Example : The Recipe and steps how to make a pizza

### Declarative and Imperative knowledge in Programming
```
Declarative
The square of a number x is y so that x∗x=y
The cube value of a number x is y so that x∗x∗x=y
```
```
Imperative
Enter a number x and the value of the power z
If the value of z is 0, then the value of the exponent is 1.
If the value of z is 1, then the value of the power is x.
If the value of z is a positive integer starting at 2, then multiply x by itself z-1 times.
```

### Algorithm
To tell the computer to do the task we want, we use an approach in the form of imperative knowledge in the form of "recipe" to do something.
In a simple "recipe" can be translated into 3 points :
1. The order of the steps
2. A sequence of control processes that specify when each step is executed.
3. Have the information when to stop and when to walk.
And all of that will create an ***"Algorithm"***

### Computer is a Machine

Computers are nothing more than machines that help us to do repetitive and tiring work.
Historically there were two types of computers :
1. Fixed Program
 Fixed program computers are very specific computers for a particular task. The simplest example of this type is a calculator.

2. Stored Program
While the stored program computer is a computer in general that we know

**Basic Computer Components**
In a stored program computer, the computer that we know in general,
there are several core components consisting of 3 major components :
1. Interface ( Interact with users )
To interact with users, Interface uses input and output
2. Processor ( Process Information )
Processor will see the sort of commands in algorithm to do a task
3. Memory ( Store Information )
Basicly, in memory there are 2 type of information : Data & Algorithm

**Programming Language**
We know that processor will see users command in Algorithm,
How do the processor know our commands? Yep, Through a Programming Language

A programming language (interpreter) is a program in a computer that is in charge of translating instructions from the user to the machine.
```
High Level Language -> Interpreter -> Machine Language
```

## Week 2

This time, we will be learning somee of python basics like Basic Operation, Variable and String

## Objects in Python
```
1. Numbers
- Integer `(1, 2, 3)`
- Float `(1.2, 2.5, 3.9)`
2. Strings
- Texts like `'Chicken','abc123','Iman_Kurnia'`
3. Tuples
A group of objects that cannot be edited `(1,2,3,2,1,5,4)`
4. Set
A group of objects that cannot be edited and no duplicate `{1,2,4,5}`
5. Dictionaries
A group of objects with key and there are no order `{'Food':'Pizza','Flavour':'Spicy'}`
6. Lists
A group of objects that you can edit `[1,2,3,4,5,5,67]`
```
## Type Conversion

We are going to change an object into Integer,Float,String,List,Tuple,Set

Expression
What is meant by expressions? An expression is something that represents something, whether it's a number or a string. So, '1010' in x variable is expression! Then, what is meant by x='1010' is a statement that makes cool get the value '1010'.
`
x = '1010'
print(x) // The Result will be 1010
type(x) // The Result will be str (string)
float_x = float(x)
print(float_x) // The Result will be 1010.0
integer_x = int(x)
print(integer_x) // The Result will be int (integer)
`

### Operators
```
Inside an expression, we can add operators that concatenate other values
1. Addition (+)
2. Substraction (-)
3. Multiplication (*)
4. Divsion (/)
5. Floor Division (//) = returns the result of division by rounding down
6. Modulo (%) = modulo will return the remain of division
7. Exponent (**)
```

**Operation Order**
Every operation in python has an order in which it operates. If there is more than one operation in one expression, then the code will be executed based on the higher priority operation :
1. parenthesis ()
2. exponent **
3. Multiplication, Division, Floor Division, and Modulo  /,*,//,%
4. Addition, Substraction  +,-

### Variables
Variables are an important element in programming. The usefulness of the variable itself is to store an information value.

To bind variables in Python / Variable assignment

```
x = 4
print(x)
output = 4
```

**Rules for Creating Variable Names**
There are a few things to keep in mind when creating variable names:
1. A variable must start with a letter or the underscore character _
2. No Space, use underscore instead
3. A variable consists of alpha-numeric characters and an underscore (A-z, 0-9, and _ )

### String

In string we can either use " or '
```
"Iman Kurnia"
'Iman Kurnia
```
String Operator
```
'Iman' + 'Kurnia'
Output = 'Imankurnia'
```
**String Methods**
capitalize() = Change the first character in the string to capitalize
find() = Searches for a string within a string, with the output being the index position of the string found
lower() = Converts all characters in the string to lowercase
lstrip() = Removes excess whitespace from the left of the string
rstrip() = Removes extra whitespace on the right side of the string
split() = Cuts the string at the specified character, and outputs it as a list
strip() = Removes extra whitespace on all sides of a string
swapcase() = Changes uppercase letters in strings to lowercase, and vice versa
title() = Converts the first letter of each word in the string to uppercase
upper() = Converts all characters in the string to uppercase

## Week 3

This time we are going to learn about Conditional and Loop in Python

### Conditional

Conditional uses if, elif, else
```
if(condition) :
  statement
elif(condition2) :
  statement2
else :
  statement3
```

> if = telling the first condition
> elif = telling the second or the next condition
> else = run the statement if there's no match condition

Example
```
X = 10

if(X<=5) :
  print('a')
elif(X<=10) :
  print('b')
else :
  print('c')

output = b
```
if x = 4 then the output is 'a'
and if x = 19 then the output is 'c' because it doesnt match the first and the second condition

### Loop
There are 2 statement for looping : while and for

**While**
```
while condition :
  statement
```
Example
```
i = 0
while i<10:
  i += 1
  print(i)

output =
1
2
3
4
5
6
7
8
9
10
```
so the statement will be run **while** it matches the condition

**While-Else**
```
i = 1
while i <= 3:
    print(i)
    i += 1
else:
    print("nilai i sudah lebih dari 3.")
 
output =
1
2
3
nilai i sudah lebih dari 3.
```

**For**
```
for variable in list:
  statement
```
Example
```
kotak_kartu = ['king', 'ace_wajik', 'ace_hati']

for kartu in kotak_kartu:
  print(kartu)]

output =
king
ace_wajik
ace_hati
```
```
for i in range(1,3):
  for j in range(1,4):
    print(i, 'x', j)
  print('ini iterasi ke ' + str(i))
  
output =
1 x 1
1 x 2
1 x 3
ini iterasi ke 1
2 x 1
2 x 2
2 x 3
ini iterasi ke 2
```

## Week 4

In this week we're going to learn about Nested-if, Pass Statement, Input, and Output

### Nested Conditional
Nested Conditional or Nested-if = a conditional statement that has another conditional statement inside of it
Usually used on a complex condition but it is very unrecommended to use because there is a chance it will error

**Nested-if**
```
If conditionA :
  If conditionB :
    statementB
  else :
    statementC
else :
  statementA
```

Examples :
```
x = 15

if x >= 10:
    if x >= 20:
        print('x is big')
    else:
        print('x is medium')
else:
    print('x is small')
    
OUTPUT : x is medium
```

2nd Example :
```
a=77

if a<50 :
    if a %2 == 0 :
      print('Small even')
    else:
      print('Small odd')
else: 
  if a %2 == 0:
      print('Big even')
  else:
      print('Big odd')

OUTPUT : Big Odd
```

## Pass Statement
Pass Statement = a condition where it didn't do anything and it will continue to the next line

** Pass Statement **
```
if conditionA:
  pass
else :
  statementA
```

Example :
```
status = True

if status == False:
  print('Open Ermegency Exit')
else:
  pass

Output :

#no output because the pass statement
```

### Input()
Input = used to collect input from user

input(prompt)
prompt = a string that will be shown if the user input a value

```
x = input("enter a value")
x

output : enter a value :
```

**Typecasting Input**
Everything we put using the Input() the system will automatically be string
Example :
```
Animal = input("Animal :")
type(Animal)

output :
str
# EVERYTHING WE INPUT IT WILL BE STRING / STR

```

So we can use typecasting to change the string
Example :

```
a = input("Enter a number: ")
b = input("Enter a decimal number: ")
a = int(a)
b = float(b)
c = a+b
c
```

```
a = int(input("Enter a number: "))
b = float(input("Enter a decimal number: "))
c = a+b
c
```

### Output
we use print() to show the output
output syntax : print(object(s), sep=separator, end=end_type)

ex :
print("Hello")
or
x = "Hello"
print(x)

**Multiple Output**
Print() can show multiple outputs
```
val1 = 3
val2 = 5.2
print('A',val1,'B',val2,'C')

output : A 3 B 5.2 C

```
or
```
val1 = 3
val2 = 5.2
print('A'+str(val1)+'B'+(val2)+'C')

output : A 3 B 5.2 C
```

**Seperator and End_Type**

Sep = Seperator, it will seperate all of the object / string in print()
Default sep=' '
if we use sep by default it will give a space

Example :
```
print('Iman','Amin','Nami','Nima',sep=' & ')

output : Iman & Amin & Nami & Nima
```

end = end_type
Default, end = '\n'
Making a new line

Example :
```
print('Iman','Amin','Nami','Nima',sep=' & ',end='>>')

output : Iman & Amin & Nami & Nima>>
```

```
for i in range(4):
    print(i, end=' ')
    
output : 0 1 2 3
```

***F-String***
in Python 3.6 we can use f-string instead of , or string concatenation

Examples :
```
name = "Budi"
print(f"ini {name}, ini bapak {name}, ini ibu {name}, ini adik {name}.")

output : ini Budi, ini bapak Budi, ini ibu Budi, ini adik Budi.
```
```
nama = 'Adi'
nilai = 90
pelajaran = 'Bahasa Inggris'
print(f"Halo {nama}! Selamat anda telah lulus tes {pelajaran} dengan nilai {nilai}")

output : Halo Adi! Selamat anda telah lulus tes Bahasa Inggris dengan nilai 90
```

***Print with %***
we can either use print with % with/without data type
Data Types with % :
```
%d - integer
%f - float
%s - string
%x - hexadecimal
%o - octa
```

example without using data type
```
hewan = 'sapi'
kaki = 4
print("Hewan %s memiliki %d kaki" %(hewan,kaki))

output : Hewan sapi memiliki 4 kaki
```

example using data type
```
barang = 'telur'
berat = 2.625
harga = 40000
print("Harga % .1f kg %s adalah %d" %(berat,barang,harga))

output : Harga  2.6 kg telur adalah 40000
```

***Print using .format()***
print with format() example :
```
print('Halo! nama saya {}, umur saya {} tahun'.format('Budi',20))

output : Halo! nama saya Budi, umur saya 20 tahun
```

positional key arguments format
example :
```
print('Teman saya, {0} bermain dengan {1}.'.format('Budi','Tono'))
print('Teman saya, {1} bermain dengan {0}.'.format('Budi','Tono'))

output :
Teman saya, Budi bermain dengan Tono.
Teman saya, Tono bermain dengan Budi.

```

keyword name format
example :
```
print('Bapak membeli {1} dan {0} sebanyak {2:.1f}L dan {vol:.2f}L dengan harga Rp.{price}'.format('bensin', 'oli', 1.542, vol=2.4752, price=50000))

output : Bapak membeli oli dan bensin sebanyak 1.5L dan 2.48L dengan harga Rp.50000
```

## Week 5

Today we are going to learn about Decompisition, Abstraction, Function, Docstring, and Lambda.

### Decomposition & Abstraction




