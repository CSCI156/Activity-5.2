#### 1. You are responsible for writing a program that will help 5000 people register for a meeting. To keep the demand down, 
people with last names 

               A<= name <= freeman are in room 121
               freeman < name <= michelson are in room 201
               michelson < name <= oppenheimer are in room 226
               oppenheimer < name <= z are in room 232

Write a procedure that takes a person’s last name and prints out their room number.

#### 2. The next program will have 10 global variables:

```
lessthan10
between10n20
between20n30
between30n40
between40n50
between50n60
between60n70
between70n80
between80n90
between90n100
```
- Write a procedure called init that sets these variables to 0.
- Write a procedure that prints out these variables.
- Write a histogram procedure. The procedure has one input and uses the ten global variables above.

Before the procedure is called these variables should be initialized to 0. The procedure histrogram will check to see where
the input lies, and increment the corresponding  global variable by 1. So histogram(43) would increment between40n50 by 1. 
Histogram(30) would increment between30n40 by 1, but would NOT increment between20n30.

#### 3. Include the random number generator package: 
```
               from random import *
```
randrange(1, 100) is the command to generate a pseudo-random between 1 and 100. Use a for loop to call histrogram with 50 
pseudo-random numbers.  Print out the global variables.


