# Linux Instructions

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

### Node.js & Git

You will then need to install Node.js, and git.  They can both be
installed with your systems standard software installer via:


#### Redhat, Fedora, CentOS

As root run the following command:

```bash
dnf install git nodejs
```

#### Debian, Ubuntu

As root run the following command:

```bash
sudo apt-get -y install git nodejs
```

### Configure Git

Set your global git username and password. At the terminal, type the following two commands. Press enter after each one:

	git config --global user.name "Your Name"
	git config --global user.email your@email.address

### Set up your SSH keys

SSH Keys are used to establish a secure connection to GitHub and Heroku.

Follow the instructions at GitHub to create and register new SSH keys: [Generating SSH Keys for GitHub](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/).

Nice work! You just set up your development environment and are already using the command line! This is serious stuff!
