Leap Motion Mouse Controller
==========
Leap controlled Mac OSX mouse. Can have rough controll of mouse by moving hand. To left-click, just wiggle your index and middle finger up and down.


Install
====

PyMouse for moving and clicking mouse. 
`sudo easy_install pymouse`


Also need access to `Leap.py` Python module in `LeapDeveloperKit/LeapSDK/lib/` to Python's path. What I did was create symbolic link to the LeapSDK folder to some target file in my project directory.


To create a symbolic link, enter:

`$ ln -s {/path/to/LeapDeveloperKit/LeapSDK} {link-name}`

Example, `cd` to the location of your project then enter this command

`$ ln -s /usr/local/LeapDeveloperKit/LeapSDK/ lib/`


Execution
====

Just execute `python ./input.py` while your Leap Motion device is plugged in. 
