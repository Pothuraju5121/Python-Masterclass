# Variables and Types  
When a program is running, everything the program needs ends up stored in the computer'e memory. The program code itself will be stored in one area of memory, and the data it works on will also be stored somewhere in memory.

    greeting = "Hello" 
    name = input("Please enter your name ")
    print(greeting + name)
    
When we create the variable called greeting, Python allocated an area of memory for us. It knows to refer ot that area whenever we talk about the variable greeting.

Because we created greeting by attaching it to a string value, Python also decided that greeting was a variable of type string, annd ensure that we can only do things with it that make sense for strings.