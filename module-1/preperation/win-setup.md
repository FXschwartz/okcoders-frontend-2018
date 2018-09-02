# Windows Instructions


You must be running a recent version of Windows, at least Windows Vista or higher. Windows 7 or higher is strongly recommended. Ensure that you have installed the latest Windows updates for you version of windows.

## Install software

Download the appropariate package for your
Linux system here:

### IDE (Text Editor for Code)
Choose one of the editors below to install.  All are free.

[Atom](https://atom.io)

[Sublime Text](http://www.sublimetext.com/)

[Visual Studio Code](https://code.visualstudio.com/)

### Browser
We will be doing all web development in Google Chrome or Firefox because of their excellent developer tools.

[Firefox](https://www.mozilla.org/en-US/)

[Google Chrome](https://www.google.com/intl/en-US/chrome/browser/)

### Git Bash

Windows does come with a built-in command prompt, but we will be using another Terminal emulator with built-in support for git, the version control software that works with GitHub. *Do not use the built-in command prompt*. Use Git Bash.

[Git Bash](http://msysgit.github.io/)

### Node.js

You will then need to install [Node.js](http://nodejs.org/)

## Configure Git

Set your global git username and password. At the terminal, type the following two commands. Press enter after each one:

	git config --global user.name "Your Name"
	git config --global user.email your@email.address


## Set up your SSH keys

SSH Keys are used to establish a secure connection to GitHub and Heroku.

Follow the instructions at GitHub to create and register new SSH keys: [Generating SSH Keys for GitHub](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/).

If you get an error when trying to add your keys to the ssh-agent, type the following command at the terminal prompt and press return:

	eval `ssh-agent -s`

Nice work! You just set up your development environment and are already using the command line! This is serious stuff!
