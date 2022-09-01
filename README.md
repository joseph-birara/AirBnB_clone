# AirBnB Clone - The console


![AirBnB](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220901%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220901T181606Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=85cb0c5646063e9805ac8405f06dde1b01d45f11eec65496cdb3a3557777ff10)

the console for airbnb project. Create a command interpreter that can modify or delete the database
The users like the administrator of the app Airbnb clone has the posibility of the manipulate objects and data of the application, this objects are:
 
 * Users
 * Places
 * States
 * Cities
 * Amenities
 * Reviews


![alt text](https://i.ibb.co/RSzZ5yh/815046647d23428a14ca.png)

## Resources
    *[cmd module](https://alx-intranet.hbtn.io/rltoken/8ecCwE6veBmm3Nppw4hz5A)
    *[uuid module](https://alx-intranet.hbtn.io/rltoken/KfL9TqwdI69W6ttG6gTPPQ)
    *[datetime](https://alx-intranet.hbtn.io/rltoken/1d8I3jSKgnYAtA1IZfEDpA)
    *[unittest module](https://alx-intranet.hbtn.io/rltoken/IlFiMB8UmqBG2CxA0AD3jA)
    *[args/kwargs](https://alx-intranet.hbtn.io/rltoken/C_a0EKbtvKdMcwIAuSIZng)
    *[python test cheeatsheet](https://alx-intranet.hbtn.io/rltoken/C_a0EKbtvKdMcwIAuSIZng)

## Requirements


## Python Scripts

    Allowed editors: vi, vim, emacs
    All your files will be interpreted/compiled on Ubuntu 14.04 LTS using python3 (version 3.4.3)
    All your files should end with a new line
    The first line of all your files should be exactly #!/usr/bin/python3
    A README.md file, at the root of the folder of the project, is mandatory
    Your code should use the PEP 8 style (version 1.7 or more)
    All your files must be executable
    The length of your files will be tested using wc
    All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
    All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
    All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')

## Python Unit Tests

    Allowed editors: vi, vim, emacs
    All your files should end with a new line
    All your test files should be inside a folder tests
    You have to use the unittest module
    All your test files should be python files (extension: .py)
    All your test files and folders should start by test_
    Your file organization in the tests folder should be the same as your project
    e.g., For models/base_model.py, unit tests must be in: tests/test_models/test_base_model.py
    e.g., For models/user.py, unit tests must be in: tests/test_models/test_user.py
    All your tests should be executed by using this command: python3 -m unittest discover tests
    You can also test file by file by using this command: python3 -m unittest tests/test_models/test_base_model.py
    All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
    All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
    All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
    We strongly encourage you to work together on test cases, so that you don’t miss any edge 
 
 
## Installation
 
 For use this console you need to have:
 * Linux ubuntu 20.04 LTS or higher
 * Python 3.8.5 or higher

## Files



 -  HBNHCommand: console.py
 -  Amenity: models/amenity.py
 -  BaseModel: models/base_model.py
 -  City: models/city.py
 -  models.init : models/__init__.py
 -  Place: models/place.py
 -  Review: models/review.py
 -  State: models/state.py
 -  User: models/user.py
 -  FileStorage: models/engine/file_storage.py
 -  engine.init: models/engine/__init__.py

```
How To run the command interpreter:
```
$ ./console.py


## Examples

Interactive mode:
```
$ ./console.py
(hbnb) help
Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
(hbnb)
(hbnb) quit
$
```
Non-interactive mode:
```
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
```

## AUTHORS
 
* **Joseph Birara** - [Joseph](https://github.com/joseph-birara)
