# Xbox 360 Controller for Python

The file `xinput.py` provides a Python interface for both Xbox 360 and Xbox One
controllers on Windows. Xbox One controllers have been tested to work despite
the name of the repository.

Under the hood, it uses the 
[XInput library](https://docs.microsoft.com/en-us/windows/desktop/xinput/getting-started-with-xinput)
and was adapted from
[Jason R. Coombs' code](http://pydoc.net/Python/jaraco.input/1.0.1/jaraco.input.win32.xinput/)
under the MIT licence terms.

The only dependency is Pyglet 1.2.4 or later. Install it by running:

	pip install pyglet
