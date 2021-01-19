# Printing in Python

The print() function prints the specified message to the screen, or other standard output device.

The message can be a string, or any other object, the object will be converted into a string before written to the screen.

### Syntax
    print(object(s), sep=separator, end=end, file=file, flush=flush)

The simplest example of using Python print() requires just a few keystrokes:

    print()
    
You don’t pass any arguments, but you still need to put empty parentheses at the end, which tell Python to actually execute the function rather than just refer to it by name. This will produce an invisible newline character, which in turn will cause a blank line to appear on your screen. You can call print() multiple times like this to add vertical space. It’s just as if you were hitting Enter on your keyboard in a word processor.

> **Newline Character**
>
> A newline character is a special control character used to indicate the end of a line (EOL). It usually doesn’t have a visible representation on the screen, but some text editors can display such non-printable characters with little graphics.
>
> They use special syntax with a preceding backslash (\) to denote the start of an **escape character sequence**. Such sequences allow for representing control characters, which would be otherwise invisible on screen.
>
> Most programming languages come with a predefined set of escape sequences for special characters such as these:
>
> * \\: backslash
> * \b: backspace
> * \t: tab
> * \r: carriage return (CR)
> * \n: newline, also known as line feed (LF)
>
>The last two are reminiscent of mechanical typewriters, which required two separate commands to insert a newline. The first command would move the carriage back to the beginning of the current line, while the second one would advance the roll to the next line.

As you just saw, calling print() without arguments results in a blank line, which is a line comprised solely of the newline character. Don’t confuse this with an empty line, which doesn’t contain any characters at all, not even the newline!

> **String Literals**
>
> String literals in Python can be enclosed either in single quotes (') or double quotes ("). According to the official PEP 8 style guide, you should just pick one and keep using it consistently. There’s no difference, unless you need to nest one in another.
>
> For example, you can’t use double quotes for the literal and also include double quotes inside of it, because that’s ambiguous for the Python interpreter:
>
>       "My favorite book is "Python Tricks""  # Wrong!
>
> What you want to do is enclose the text, which contains double quotes, within single quotes:
>
>       'My favorite book is "Python Tricks"'
>
> The same trick would work the other way around:
>
>       "My favorite book is 'Python Tricks'"
>
> Alternatively, you could use escape character sequences mentioned earlier, to make Python treat those internal double quotes literally as part of the string literal:
>
>       "My favorite book is \"Python Tricks\""

Lastly, you can define multi-line string literals by enclosing them between ''' or """, which are often used as docstrings.

Here’s an example:  
        """  
This is an example  
of a multi-line string  
in Python.  
"""
