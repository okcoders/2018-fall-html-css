Windows Instructions
====

You must be running a recent version of Windows, at least Windows Vista or higher. Windows 7 or higher is strongly recommended. Ensure that you have installed the latest Windows updates for you version of windows.

## Install software

Install the following software by downloading it at these urls:

[VSCode](https://code.visualstudio.com/)

This is what I will be using in the class, with a few quality of life extensions installed. 

Once you've installed VSCode, make sure to also install the command line tool. 

1. While VSCode is open, open the command palette by pressing `ctrl + shift + p`
	- the command palette contains commands that your text editor can perform (eg. creating a new file, copying a file, etc.)
2. Type `install command`, and select the first option that reads

```
Shell Command: Install 'code' command in PATH
```

3. Close VSCode and any terminal windows you might have open, and reopen the terminal.
4. Type `code` into the terminal and VSCode should launch.


[Google Chrome](https://www.google.com/intl/en-US/chrome/browser/).

We will be doing all web development in Google Chrome because of its excellent developer tools.

[Git Bash](http://msysgit.github.io/)

Windows does come with a built-in command prompt, but we will be using another Terminal emulator with built-in support for git, the version control software that works with GitHub. *Do not use the built-in command prompt*. Use Git Bash.

## Configure Git

Set your global git user name and email. At the terminal, type the following two commands. Press enter after each one:

	git config --global user.name "Your Name"
	git config --global user.email your@email.address

## Install Node and Friends

Install Node.js: [http://nodejs.org/](http://nodejs.org/).

## Set up your SSH keys

SSH Keys are used to establish a secure connection to GitHub and Heroku.

Follow the instructions at GitHub to create and register new SSH keys: [Generating SSH Keys for GitHub](https://help.github.com/articles/generating-ssh-keys).

If you get an error when trying to add your keys to the ssh-agent, type the following command at the terminal prompt and press return:

	eval `ssh-agent -s`

Nice work! You just set up your development environment and are already using the command line! This is serious stuff!
