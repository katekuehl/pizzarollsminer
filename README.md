# pizzarollsminer #
	KateKuehl
	Code to Figure Out Everywhere in the US where you can get Pizza Rolls

Warnings: This code is currently under construction. I don't guarantee the soundness of the data nor do I take responsibilty for frustration (yet). 
	This code involves mining for data. I do not take responsibility for any agreements, terms, conditions or laws you break while using this code. All this code is theoretical, as such I have not used it to mine data. If you abuse the code, there is a strong possibility of your IP getting banned. Go at your own risk.  


Note: These instructions are for Windows 10 - you'll likely have to adjust them if you are using a different Operating System

To start:
- Make sure you have Python3 Installed - https://www.python.org/downloads/
- Update pip to the latest version by typing the following into the commandline
	python -m pip install -U pip setuptools
- Type the following command into command line to get my version of the python zipcode module
	git clone https://github.com/katekuehl/zipcode

Using Pycharm:
- I recommend using the Pycharm IDE (https://www.jetbrains.com/pycharm/) but it's certianly not necessary
	-In Pycharm you might need to import the requests, sqlite3 and halversine modules (https://www.jetbrains.com/help/pycharm/2016.1/installing-uninstalling-and-upgrading-packages.html)
- On Pycharm go to File -> Open.. then find and click on the zipcode file then press "OK". On the "Open Project" window choose "Open in current window" and "Add to currently opened projects" then press "OK".


If you don't use Pycharm:
- Import the necessary modules by typing 
	pip install requests
	pip install sqlite3
	pip install haversine
- Add zipcode as a local module
	import sys
	sys.path.append("/path/to/your/zipcode/directory")
	import zipcode

Now you can run __init__.py and access the functions within the code!