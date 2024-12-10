[![alt text](https://ibb.co/6vXZ314)](https://ibb.co/6vXZ314)

### holbertonschool-Markdown2HTML

## Requirement
Requirements
All your files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7 or higher)
The first line of all your files should be exactly #!/usr/bin/python3
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the PEP 8 style (version 1.7.*)
All your files must be executable
All your modules should be documented: python3 -c 'print(__import__("my_module").__doc__)'
Your code should not be executed when imported (by using if __name__ == "__main__":)
You are not allowed to use python’s library Markdown.

## Task0 - Start a script
script markdown2html.py that takes an argument 2 strings:

First argument is the name of the Markdown file
Second argument is the output file name
Requirements:

If the number of arguments is less than 2: print in STDERR Usage: ./markdown2html.py README.md README.html and exit 1
If the Markdown file doesn’t exist: print in STDER Missing <filename> and exit 1
Otherwise, print nothing and exit 0

## Task1 - Headings
Improve the file by parsing Headings Markdown syntax for generating HTML
![Alt text](https://ibb.co/QHX2vV9)


## Task2 - Unordered listing
Improve the file by parsing Unordered listing syntax for generating HTML
Syntax: 
  * Markdown:
    - Hello
    - Bye

  * HTML generated:
    <ul>
        <li>Hello</li>
        <li>Bye</li>
    </ul>

## Task3 - Ordered listing
Improve the file by parsing Ordered listing syntax for generating HTML
Syntax:
  * Markdown:
    * Hello
    * Bye
    
  * HTML generated:
    <ol>
        <li>Hello</li>
        <li>Bye</li>
    </ol>

## Task4 - Simple text
Improve the file by parsing paragraph syntax for generating HTML:
Syntax:
  * Markdown:
    Hello

    I'm a text
    with 2 lines

  * HTML generated:
    <p>
        Hello
    </p>
    <p>
        I'm a text
            <br />
        with 2 lines
    </p>

## Task5 - Bold and emphasis text
Improve the file by parsing bold syntax for generating HTML
![Alt text](https://ibb.co/PcjD71c)

## Task6 - different syntax
![Alt text](https://ibb.co/dtcts4p)
