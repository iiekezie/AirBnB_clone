## Project Overview
Welcome to the AirBnB clone project! This project involves writing a command interpreter to manage your AirBnB objects. This is the first step towards building your first full web application: the AirBnB clone. This step is crucial because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration, etc.


## Table of Contents

1. [Project Overview](#project-overview)
2. [Technologies](#technologies)
3. [Requirements](#requirements)
4. [General](#general)
5. [Directory Structure](#directory-structure)
6. [Tasks](#tasks)
7. [C Scripts](#c-scripts)
8. [Author](#author)

## Technologies
- Python
- OOP (Object-Oriented Programming)
- cmd module
- JSON

## Requirements

### General
- All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the pycodestyle (version 2.7.*)
- All your files must be executable
- The length of your files will be tested using wc
- All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
- All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
- All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
- A documentation is not a simple word, it’s a real sentence explaining the purpose of the module, class, or method (the length of it will be verified)
- All your unittests should be in the tests folder and should be able to be executed by using this command: python3 -m unittest discover tests

## Directory Structure

```
AirBnB_clone/
│
├── console.py
├── models/
│   ├── base_model.py
│   ├── __init__.py
│   ├── engine/
│   │   ├── file_storage.py
│   │   ├── __init__.py
│   ├── user.py
├── tests/
│   ├── test_base_model.py
│   ├── test_file_storage.py
│   ├── test_user.py
├── README.md
└── AUTHORS
```

## Tasks

| Task Number | File Name                    | Description                                                                                      |
|-------------|------------------------------|--------------------------------------------------------------------------------------------------|
| 0           | README.md, AUTHORS           | Write a README file and an AUTHORS file.                                                         |
| 1           | All source files             | Ensure code is pycodestyle compliant.                                                            |
| 2           | tests/                       | Write unittests for all your files, classes, and functions.                                      |
| 3           | models/base_model.py         | Create BaseModel class with common attributes/methods for other classes.                         |
| 4           | models/base_model.py         | Create BaseModel from dictionary representation.                                                 |
| 5           | models/engine/file_storage.py| Serialize instances to a JSON file and deserialize JSON file to instances.                       |
| 6           | console.py                   | Write a program that contains the entry point of the command interpreter.                        |
| 7           | console.py                   | Update your command interpreter to have these commands: create, show, destroy, all, update.      |
| 8           | models/user.py               | Write a User class that inherits from BaseModel and update FileStorage to manage it correctly.   |
| 9           | console.py                   | Update command interpreter to support <class name>.all(), <class name>.count() methods.          |
| 10          | console.py                   | Update command interpreter to support <class name>.show(<id>), <class name>.destroy(<id>) methods.|
| 11          | console.py                   | Update command interpreter to support <class name>.update(<id> <attribute name> "<attribute value>").|
| 12          | console.py                   | Update command interpreter to support <class name>.update(<id> <attribute name> <attribute value>). |
| 13          | console.py                   | Update command interpreter to support <class name>.update(<id> <dictionary representation>).     |
| 14          | models/place.py              | Write a Place class that inherits from BaseModel and update FileStorage to manage it correctly.  |
| 15          | models/city.py               | Write a City class that inherits from BaseModel and update FileStorage to manage it correctly.   |
| 16          | models/amenity.py            | Write an Amenity class that inherits from BaseModel and update FileStorage to manage it correctly. |
| 17          | models/review.py             | Write a Review class that inherits from BaseModel and update FileStorage to manage it correctly. |

## C Scripts
N/A

## Author
* **Ifeanyi I Ekezie** - [iiekezie](https://github.com/iiekezie)
