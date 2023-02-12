0x00. AirBnB clone - The console

The goal of this project is to deploy on our server a simple copy of the AirBnB website.

We won’t implement all the features, only some of them to cover all fundamental concepts of the higher level programming track.

Our application will be composed by:

A command interpreter to manipulate data without a visual interface, like in a Shell
A website that shows the final: static and dynamic
A database or files that store data
An API that provides a communication interface between the front-end and our data
🖥 The command interpreter
Execution
The command interpreter can be launched in interactive or non-interactive mode as follows:

Interactive Mode: $ ./console.py
Non-interactive Mode: $ echo <command> | ./console.py
Usage
The command interpreter currently handles:

all [class_name] - prints all string representation of all instances (or of the specified class_name)
Can also be used as <class_name>.all()
create <class_name> - creates a new instance of BaseModel, saves it and prints the id
<class_name>.count() - prints the number of instances of a class
destroy <class_name> <id> - deletes an instance
Can also be used as <class_name>.destroy(<id>)
quit OR ⌃ + D (EOF) - exits the program
show <class_name> <id> - prints the string representation of an instance
Can also be used as <class_name>.show(<id>)
update <class_name> <id> <attribute_name> <attribute_value> - updates an instance by adding or updating attribute
Can also be used as <class_name>.update(<id>, <attribute_name>, <attribute_value>) OR <class_name>.update(<id>, <dictionary_representation>)
Example of use. 
[vagrant@ubuntu AirBnB_clone ]$ ./console.py
(hbnb) help

