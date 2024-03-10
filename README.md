*0x00 AirBnB clone - The console*

*Project description*

The Airbnb project aims to develop a clone of the AirBnb online application that assists in the rental of holiday accommodation which is available on a short or long term basis. The project involves functionalities used in the backend.

*Command interpreter description*

        - The command line interpreter program will accept commands and then executes the commands to the shell. The backend of the program is developed using Python Object orientated programming(OOP).

*How to start it*

        - Create a new object (ex: a new User or a new Place)
        - Retrieve an object from a file, a database etc▒~@▒
        - Do operations on objects (count, compute stats, etc▒~@▒)
        - Update attributes of an object
        - Destroy an object

*How to use it*

The application can be used in two different modes namely interactive and non-interactive mode. Once the command has finished executing the prompt is displayed waiting for new instructions by the user.

*Interactive mode:*

In interactive mode, it displays the prompt where users able to input and carry out commands. Once the command has been displayed in the output, the prompt is displayed again waiting for new instructions by the user.

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$

*Non-interactive mode*

Non-interactive mode of the shell does not interact with the user. This mode is run utilizing a script.

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
