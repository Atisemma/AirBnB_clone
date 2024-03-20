# Project Name

0x00. AirBnB clone - The console

## Description

AirBnb clone - The Console projects provides a set of skills for learners so that they can practice their software development skills related to web development and specialization in back end using Python programming language. It also supports community development since learners contribute, share and code along to build and understand the infrastructure of the web design.
Modules - python3 -c 'print(__import__("my_module").__doc__)'
Classes - python3 -c 'print(__import__("my_module").MyClass.__doc__)'
Functions - python3 -c 'print(__import__("my_module").my_function.__doc__)'
python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'

## How to Start

To start the AirBnb clone - The console, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/Atisemma/AirBnB_clone.git
    ```

2. Navigate to the project directory:

    ```bash
    cd AirBnB_clone
    ```

3. Run the command interpreter:

    ```bash
    python interpreter.py
    ```

## How to Use

Once the command interpreter is running, you can use the following commands:

- `help`: Display a list of available commands and their descriptions.
- `run <script>`: Execute a script file.
- `list`: List all files in the current directory.
- `create <file>`: Create a new file.
- `delete <file>`: Delete a file.
- `exit`: Terminate the command interpreter.

## Examples

1.  Interactive Mode:
```bash
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$

2.  Non-interactive Mode:
```bash

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$

3. Running Test in Non-Interactive Mode and Additional Test 

$ echo -e "python3 -m unittest discover tests\n\ncat test_help\nhelp" | bash | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)

4. All tests should aldo pass this command in non-interactive mode:

$ echo "python3 -m unittest discover 

### Contributors

- Faith Akinyi <faithomondi1331@gmail.com>
- Emma Ogutu <atisemma27@gmail.com>
