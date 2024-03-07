Project Description
Learn how to create a Python package. How to create a command interpreter in Python using the cmd module. What is Unit testing and how to implement it in a large project. How to serialize and deserialize a Class. How to write and read a JSON file. How to manage datetime. What is an UUID. What is *args and how to use it. What is **kwargs and how to use it. How to handle named arguments in a function.

Commmand Interpreter Description and Execution
Start the command interpreter as shown below:

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
But also it can be started like this in non-interactive mode: (like the Shell project in C):

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)

