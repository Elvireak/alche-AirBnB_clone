# AirBnB Clone - The Console

## Description
This project is the first step of the AirBnB clone, a full web application.
It is a command interpreter (like a small shell) that lets you create,
show, update, and delete objects such as User, Place, City, and State.
Objects are saved to a JSON file so they are kept between runs.

## Command Interpreter
### How to start it
Interactive mode:
```
$ ./console.py
(hbnb)
```
Non-interactive mode:
```
$ echo "help" | ./console.py
```

### How to use it
| Command | What it does |
|---|---|
| `help` | Shows the list of commands |
| `quit` / `EOF` | Exits the program |
| `create <class>` | Creates a new object and prints its id |
| `show <class> <id>` | Prints one object |
| `destroy <class> <id>` | Deletes one object |
| `all [<class>]` | Prints all objects (or all of one class) |
| `update <class> <id> <attr> "<value>"` | Changes an attribute |

### Examples
```
(hbnb) create BaseModel
49faff9a-6318-451f-87b6-910505c55907
(hbnb) show BaseModel 49faff9a-6318-451f-87b6-910505c55907
(hbnb) quit
```

## Authors
See the AUTHORS file.
