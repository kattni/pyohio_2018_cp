## Setup
For this tutorial, participants will want to install Mu editor. More advanced participants may
install Atom or PyCharm. If not using Mu, to access the serial console use `screen` on
Mac, or Linux, or PuTTY on Windows. Everyone may wish to install Mu, however, as there are a few
examples that make use of the plotter function in Mu.

Mu 1.0 was released on 20 July 2018. If you installed Mu before this, please update to the most
recent version.

## To install Mu editor on Mac or Windows:
Windows users may install Mu from [here](https://codewith.mu/en/download).

Mac users may install Mu from [here](https://codewith.mu/en/download).

## To install Mu editor on Linux x86:
Linux users must install Python 3 by running `sudo apt install python3`. Then, install
`pip3` by running `sudo apt install python3-pip`.

Next, create a virtual environment: `python3 -m venv pyohiocp`. To activate the virtual
environment, run `source ~/pyohiocp/bin/activate`. Once inside the virtual environment
`(pyohiocp)`, run `pip3 install --upgrade pip` to bring `pip3` up-to-date. Then, install Mu by
running `pip3 install mu-editor`.

Linux users must also add their user to the dialout group. From the command line, run
`nano /etc/group`. Find the line with `dialout:` and add your user to the end, after a comma
with no space, i.e. `dialout:foo,your_user`.

## Running Mu editor
To run Mu on Windows, double-click the icon.

To run Mu on Mac, double-click the icon in the Applications folder.

To run Mu on Linux, from inside the virtual environment, type `python3 -m mu` into the
command line.

## Inside Mu editor
Once Mu is opened, it will present a list of options. For this tutorial, choose "Adafruit
CircuitPython".

If there is no CircuitPython compatible board plugged in when the editor is opened, there will
be a dialog box that starts with "Could not find an attached Adafruit CircuitPython device".
This is normal.

## Code for Tutorial
This repo contains all the code used in the tutorial. To access it during the tutorial,
participants can view it on the web, and copy and paste as they follow along. They may wish to
have the files available locally. To do this, install `git` and clone the repo to your machine
using `git clone https://github.com/kattni/pyohio_2018_cp` to create a directory containing the
contents of the repo.

Please do a `git pull` on this cloned repository either *in the evening of Saturday July 28 or 
in the morning of Sunday July 29*.