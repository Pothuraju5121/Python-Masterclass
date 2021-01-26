# Variables and Types  
When a program is running, everything the program needs ends up stored in the computer'e memory. The program code itself will be stored in one area of memory, and the data it works on will also be stored somewhere in memory.

    greeting = "Hello" 
    name = input("Please enter your name ")
    print(greeting + name)
    
When we create the variable called greeting, Python allocated an area of memory for us. It knows to refer ot that area whenever we talk about the variable greeting.

Because we created greeting by attaching it to a string value, Python also decided that greeting was a variable of type string, annd ensure that we can only do things with it that make sense for strings.

### There are few rules for variable names:
* Python variable names must begin with a letter (either upper or lower case) or an underscore _ character.
* They can contain letters, numbers or underscore character (but cannot begin with a number).
* Python variables are case sensitive, so greeting and Greeting would refer to 2 different variables.
* variables are created when they are first attached to a value, using =.


| Operators | Description | Example |
|-----------|-------------|---------|
| + Addition | Adds values on either side of the operator. | a+b=30 |
| - Subtraction | Subtracts right hand operand from left hand operand. | a-b=-10|
| * Multiplication | Multiplies values on either side of the operator | a*b=200 |
| / Division | Divides left hand operand by right hand operand | b/a=2 |
| % Modulus | Divides left hand operand by right hand operand and returns remainder | b%a=0 |
| ** Exponent | Performs exponential (power) calculation on operators | a**b =10 to the power 20 |
| // Floor Division | 	Floor Division - The division of operands where the result is the quotient in which the digits after the decimal point are removed. But if one of the operands is negative, the result is floored, i.e., rounded away from zero (towards negative infinity) − | 9//2 = 4 and 9.0//2.0 = 4.0, -11//3 = -4, -11.0//3 = -4.0| 


| H |   | r |   |  |   |   |  |  |  |   |  |
|---|---|---|---|--|---|---|---|---|---|---|---|
| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 |
| -12 | -11 | -10 | -9 | -8 | -7 | -6 | -5 | -4 | -3 | -2 | -1 |
