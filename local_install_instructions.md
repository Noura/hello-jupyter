Installing Python and Jupyter
===============

We are going to use Python in this class. Installing Jupyter is not 100% required, but it's a good idea because a lot of code from class will be shared in the form of Jupyter notebooks.

I'm trying to keep these instructions short and link to other pages who explain stuff in more depth. But that said, if you get stuck, just email me and I can help you troubleshoot! (noura@berkeley.edu)

1. Open the terminal
--------

Launch a terminal (aka command line, command prompt). Instructions:
[OSX](http://blog.teamtreehouse.com/introduction-to-the-mac-os-x-command-line) , [Windows](http://www.howtogeek.com/235101/10-ways-to-open-the-command-prompt-in-windows-10/)

Things that we ask you to type into your terminal will be formatted like this:
	
	$ cd
	
The `$` part represents what you will probably see leftmost in every line in the terminal. For example, on my terminal it shows `noura ~ $`. The `cd` is the part you actually type in and then hit ENTER. (This notation isn't universal. Sometimes other people will write commands that you are supposed to type in the terminal like `cd` without the `$`, and sometimes they use `>>>` instead of `$`...)

2. Install Python
--------
Actually chances are you already have it installed. Check if you already have it installed by running this command in the terminal:

	$ python -V
	
If you have Python, this will tell you what version you have. If you do not have Python, you'll get an error message.
	
Make sure your version of Python is recent enough. It needs to be either 2.7 or higher or 3.3 or higher.

If you do not have Python installed, or if the version number is too low, installing or upgrading are both done by downloading Python from here: [instructions](https://wiki.python.org/moin/BeginnersGuide/Download)
	
If you already have Python2, I think it would be simplest to just get the latest version of Python2. And same for Python3 - If that's what you already have stick with that. Why two major different versions of Python are both still in use is a matter of much discussion on the internet. I'm not going to take a stance here; just trying to make this setup process as simple as possible.

NOTE: If you are on OSX El Capitan, chances are you already have Python 2 installed, but I would recommend going ahead and installing Python 3 and using that for Jupyter. Some students were having trouble installing Jupyter with Python 2 on El Capitan but switching to Python 3 seems to have fixed the problem. 
	
3. Install Jupyter
------
Go to the [Jupyter Instructions](http://jupyter.readthedocs.org/en/latest/install.html#install) and follow the section for "Installing Jupyter (I already have Python)" and "Using pip", then follow the link for "next steps" at the end of the "Using pip" section.
	

