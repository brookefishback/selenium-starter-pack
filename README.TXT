########################################################################################################################
The purpose of this script is to walk through all steps needed to get started with selenium - installing packages, python, etc and give a very simple script that performs a task.
After walking through the README, you will have a complete set up to create your own projects and solve problems with automation.
########################################################################################################################


### PREREQUISTES (INSTALLATIONS)
# HOMEBREW
# PYTHON
# PIP
# SELENIUM
# CHROMEDRIVER

### USING THE SCRIPT
# RUNNING LOCALLY
# WHAT YOU WILL SEE


###### PREREQUISTES

### Install HOMEBREW
HOMEBREW is a package manager that will find and install all packages for you, keep them organized and let you know when there are updates available.

# Run the command below in your terminal to install HOMEBREW:
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

### Install PYTHON
Python is a general purpose programming language (basically meaning it can be used for anything).
You'll most frequently see Python for backend web development, data analysis or for automation like this script! 

# Run the command below to see if PYTHON is already installed your OS
$ python --version

# The output will be 'Python 2.7.16' which confirms that Python is installed and the particular version. If there is an error, or you want to use a newer version, you can run the command below
$ brew install python

#If you want a specific version of python, use this format to install
$ brew install python3

### Install PIP
Python has a few package managers but pip is the preferred one. For reference, pip = pip installs package. There is a dependency to pip (--distribute) that Homebrew won't install.

# Run these commands to get --distribute and PIP
$ curl -O http://python-distribute.org/distribute_setup.py
$ python distribute_setup.py
$ curl -O https://raw.github.com/pypa/pip/master/contrib/get-pip.py
$ python get-pip.py

### Install SELENIUM
Selenium is an open source automation tool that uses PYTHON API's to connect to browsers and send commands.

# Run the command below to get selenium
$ pip3 install selenium

### Install CHROMEDRIVER and set executable in system path
You can use IE, Firefox, etc webdrivers but I prefer Chrome.

# Download the CHROMEDRIVER that is compatible with your version of Chrome at the link below, I included v80 in the .zip under demo > webdriver.
https://chromedriver.chromium.org/downloads

# Set webdriver executable path
Open terminal and run the command below
$ sudo nano /etc/paths
Enter your password
Add your path to the bottom of the file
My PATH looks like: /Users/brfishba/Desktop/demo/webdriver
Control-x to quit
Y to save
Press enter to confirm

##### USING THE SCRIPT 

### Running locally

# Visual Studio Code
I like to use Visual Studio Code, which is an IDE with a terminal as well. I can run the script and make edits in between sessions very easily.
https://code.visualstudio.com/download

### What you will see
A headless Chrome browser will open Google
