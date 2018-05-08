## Setup
For this tutorial, participants will want to install Mu editor. If desired, more advanced participants can install Atom or PyCharm and use `screen` on Mac or Linux, or PuTTY on Windows - however this will mean not participating in a small part of the tutorial as there are a few examples that make use of the plotter function in Mu editor.

Regardless of operating system, participants will need to install Python 3. On Windows, it's easiest to download the IDE from the [Python.org](https://www.python.org/downloads/) (tick the "Add paths" box on installation). On Mac, install [Homebrew](https://brew.sh/), and then run `brew install python3`. On Linux, run `sudo apt install python3`.

## To install Mu editor:
Participants will will need to install pip. For Windows, pip is included with the Python 3 install. For Mac OS, type `brew install pip3`. On Linux, run `sudo apt install python3-pip`.

Windows users must know how to create a virtual environment and be able to access the serial port. Once in the virtual environment, install Mu by running `pip3 install mu-editor`.

Linux users must create a virtual environment: `python3 -m venv pyohiocp`. To activate the virtual environment, run `source ~/pyohio/bin/activate`. Once inside the virtual environment, install Mu by running `pip3 install mu-editor`.

Mac users should install Mu by running `pip3 install mu-editor`.

Linux users must also add their user to the dialout group. From the command line, run `nano /etc/group`. Find the line with `dialout:` and add your user to the end, after a comma with no space, i.e. `dialout:foo,your_user`.

## Running Mu editor
To run Mu on Windows, from inside the venv, type `mu` into the command prompt.

To run Mu on Mac, type `mu` into the command line.

To run Mu on Linux, from inside the venv, type `python3 -m mu` into the command line.