Windows Instructions
====

You must be running a recent version of Windows, at least Windows Vista or higher. Windows 7 or higher is strongly recommended. Ensure that you have installed the latest Windows updates for you version of windows.

## Install software

Install the following software by downloading it at these urls:

[Google Chrome](https://www.google.com/intl/en-US/chrome/browser/).

We will be doing all web development in Google Chrome because of its excellent developer tools.

[Git Bash](http://msysgit.github.io/)

Windows does come with a built-in command prompt, but we will be using another Terminal emulator with built-in support for git, the version control software that works with GitHub. *Do not use the built-in command prompt*. Use Git Bash.


[VSCode](https://code.visualstudio.com/)

This is what I will be using in the class, with a few quality of life extensions installed. 

Once you've installed VSCode, double check that the `code` command works inside of git bash. 

1. open git bash
2. type `code --v`

If you get output other than a `command not found` error, you're good to go.

To open a file in VSCode, type `code <name of file>` into git bash (make sure you're in the right directory).

To open a folder in VSCode, type `code .` into git bash, while you're in the directory. Or simply the path to the folder.

## Configure Git

Set your global git user name and email. At the terminal, type the following two commands. **Note: The email address should be the same as your github account.** Press enter after each one:

	git config --global user.name "Your Name"
	git config --global user.email your@email.address

## Install Node and Friends

Install Node.js: [http://nodejs.org/](http://nodejs.org/).

Note: Make sure to install the LTS (long term support) version of Nodejs. 

## Set up your SSH keys

SSH Keys are used to establish a secure connection to GitHub and Heroku.

Follow the instructions at GitHub to create and register new SSH keys: [Generating SSH Keys for GitHub](https://help.github.com/articles/generating-ssh-keys).

Note: When you're entering a password during this process it **will not** show up in the terminal. This is for security reasons.

If you get an error when trying to add your keys to the ssh-agent, type the following command at the terminal prompt and press return:

	eval `ssh-agent -s`

Nice work! You just set up your development environment and are already using the command line! This is serious stuff!
