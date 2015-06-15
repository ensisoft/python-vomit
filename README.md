# python-vomit
Python Interface Wrapper

What this is?
--------------

Classes for importing and invoking Python scripts as well as registering
new native C++ based modules to the Python interpreter for the scrtips to call.

Thread safe.


How to Use?
-----------
You'll need Python 2x (tested with Python 2.7)

In your C++ code initialize a python::program 

export (or use setenv) to use PYTHONPATH to point to the place
where your scripts are and then it should just work. (fingers crossed)

There's also a exception.py script which is used to format
an exception inside python to provide for more detailed information
about what went wrong. If you wan't this you need to stick that
script to some location where it can be found and loaded by the 
interpreter.


