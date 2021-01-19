# Printing in Python

The print() function prints the specified message to the screen, or other standard output device.

The message can be a string, or any other object, the object will be converted into a string before written to the screen.

### Syntax
    print(object(s), sep=separator, end=end, file=file, flush=flush)

The simplest example of using Python print() requires just a few keystrokes:

    print()
    
You don’t pass any arguments, but you still need to put empty parentheses at the end, which tell Python to actually execute the function rather than just refer to it by name. This will produce an invisible newline character, which in turn will cause a blank line to appear on your screen. You can call print() multiple times like this to add vertical space. It’s just as if you were hitting Enter on your keyboard in a word processor.

> **Newline Character**

> A newline character is a special control character used to indicate the end of a line (EOL). It usually doesn’t have a visible representation on the screen, but some text editors can display such non-printable characters with little graphics.

> They use special syntax with a preceding backslash (\) to denote the start of an **escape character sequence**. Such sequences allow for representing control characters, which would be otherwise invisible on screen.

> Most programming languages come with a predefined set of escape sequences for special characters such as these:

> * \\: backslash
> * \b: backspace
> * \t: tab
> * \r: carriage return (CR)
> * \n: newline, also known as line feed (LF)
