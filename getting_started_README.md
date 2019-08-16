# python_training

Python is a general-purpose programming language created in the early 1990s by Guido van Rossum at Stichting Mathematisch Centrum. It is noted for it's readability (driven by the significant use of white space) and support for multiple programming paradigms (functional, object-oriented, etc.). The most current version, Python 3, was released in 2008, alongside the legacy version, Python 2.X which will be phased out by 2020.


# install python
python_training will begin with installation of the latest release, Python 3.7.4 (as of 15 August 2019) from the Python Software Foundation website: https://www.python.org/downloads/

Select the 64 bit executable installer to download.

Check the 'Add Python 3.7 to PATH' box then select 'Customize Installation' (we will want to specify our folder locations for training ease). Select all optional items for installation. Our file path will follow the syntax "username\Python".

Once the executable installer is complete, you may be promoted to modify your PATH limit. Do this if permissions allow.


# check your python install
To test successful installation, navigate to the folder in the command line:

ex.

c:

[return]

cd Users\username\Python

[return]

dir

[return]


This should navigate you to the appropriate disk, then to the folder to which you install Python. Finally, you'll print the contents of the directory and be able to verify python37.dll is present.


# get a text editor
Now it's time for your text editor. Navigate your browser to https://notepad-plus-plus.org/download/v7.7.1.html, download the 64 bit executable installer, open, and proceed with installation.

I would recommend following the same file path structure as was used for the Python installation (disk:\Users\username\Notepad++).

Proceed with the 'Minimalist Installation' and select 'Auto-completion files', 'Plugins', and 'Plugins Admin'.


# run your first program
To test successful isntallation, open Notepad++, type "print('Almost finished!')", and save the file as "test.py" to your desktop -- don't forget the .py extension!

Now, you're ready to execute your first Python script.

Navigate to your Desktop folder in the command line and execute the script:

ex.

python test.py

[return]


If your PATH is properly constructed, you should see "Almost finished!" printed in the console.


# setting up your IDE
To ease in code development, we're going to install an IDE, an integrated development environment. Our IDE of choice is Jupyter: https://jupyter.readthedocs.io/en/latest/content-quickstart.html


# pip install
To install Jupyter, we're going to use PIP - a package management system.

First, upgrade pip:

python -m pip install --upgrade pip

Then, install Jupyter notebooks:

python -m pip install jupter


# test Jupyter
Once complete, you're ready to begin the training with the workbooks in this repository.















