![hbnb_logo](https://user-images.githubusercontent.com/56078297/183303265-d80bc1f0-ce04-48c0-a4e2-25a7277d70e1.png)
# **HOLBERTONBNB PROJECT**
## **AIRBNB CLONE**

# *Description*
HolbertonBnB is a complete web application, integrating database storage, a back-end API, and front-end interface in a clone of AirBnB.

This team project is part of the (Alx) Holberton School Software Engineering program.
It represents the first step towards building a full web application.

This first step consists of:
- a custom command-line interface for data management,
- and the base classes for the storage of this data.

# *Usage*

|  *Command*         |    *Examples*                             |
|--------------------|-------------------------------------------|
|Run the console     |./console.py                               |
|quit the console    |(hbnb) quit                                |
|Create an object    |(hbnb) create <class>                      | 
|Show an object      |(hbnb) show <class> <id>                   |
|Destroy an object   |(hbnb) destroy <class> <id>                |

and more.

**Interactive mode(example)**

'''

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
'''
**Non-interactive mode**

'''

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
$
'''

# *Testing*
Unittests for the HolbertonBnB project are defined in the tests folder. To run the entire test suite simultaneously, execute the following command:

'''
$ python3 unittest -m discover tests
'''

Alternatively, you can specify a single test file to run at a time:

'''
$ python3 unittest -m tests/test_console.py
'''

# *Authors*

- Admas Girma [Son-OfAnton](https://www.github.com/Son-OfAnton).
- Wendwosen Dufera [wendecoder](https://www.github.com/wendecoder).


