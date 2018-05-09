## Setup
For this tutorial, participants will want to install Mu editor. More advanced participants may install Atom or PyCharm. Serial port access to the Circuit Python Express may use `screen` on Mac or Linux or PuTTY on Windows. Folks may wish to install Mu anyway as there are a few examples that makes use of the plotter function in Mu editor.

Participants will need to install Python 3. On Windows, it's easiest to download the IDE from the [Python.org](https://www.python.org/downloads/) (tick the "Add paths" box on installation). On Mac, install [Homebrew](https://brew.sh/), and then run `brew install python3`. On Linux, run `sudo apt install python3`.

## To install Mu editor:
Participants will will need to install pip:
 * Windows: pip is included with the Python 3 install.
 * Mac OS: type `brew install pip3`.
 * Linux: run `sudo apt install python3-pip`.

Windows users must know how to create a virtual environment and be able to access the serial port. Once in the virtual environment, install Mu by running `pip3 install mu-editor`.

Linux users must create a virtual environment: `python3 -m venv pyohiocp`. To activate the virtual environment, run `source ~/pyohio/bin/activate`. Once inside the virtual environment, install Mu by running `pip3 install mu-editor`.

Mac users should install Mu by running `pip3 install mu-editor`.

Linux users must also add their user to the dialout group. From the command line, run `nano /etc/group`. Find the line with `dialout:` and add your user to the end, after a comma with no space, i.e. `dialout:foo,your_user`.

## Running Mu editor
To run Mu on Windows, from inside the venv, type `mu` into the command prompt.

To run Mu on Mac, type `mu` into the command line.

To run Mu on Linux, from inside the venv, type `python3 -m mu` into the command line.

## Inside Mu editor
Once you've opened Mu, it will present you with a list of options. For this tutorial, choose "Adafruit CircuitPython". 

If there is no CircuitPython compatible board plugged in when the editor is opened, there will be a dialog box that starts with "Could not find an attached Adafruit CircuitPython device". This is normal. 
