Macintosh Instructions
====

You must be running Mac OS 10.8 Mountain Lion or Mac OS 10.9 Mavericks. Check what version of the Mac OS you have installed by clicking on the Apple menu item at the top left of your screen and selecting *About this Mac*.

If you must upgrade your computer, follow the instructions at [apple.com/osx/how-to-upgrade](http://www.apple.com/osx/how-to-upgrade/).

Also ensure that you have installed the latest updates. Again click on the *Apple* menu item at select *Software Update*.

## Install Software

Install the following software by downloading it at these urls:

If you do not already have a preferred editor, then check out [VSCode](https://code.visualstudio.com/)

Once you've installed VSCode, make sure to also install the command line tool. 

1. While VSCode is open, on the command palette by pressing `cmd + shift + p`
2. Type `install command`, and select the first option that reads

```
Shell Command: Install 'code' command in PATH
```

3. Close VSCode and any terminal windows you might have open, and reopen the terminal.
4. Type `code` into the terminal and VSCode should launch.

This is what I will be using in the class, with a few quality of life extensions installed. 

[Google Chrome](https://www.google.com/intl/en-US/chrome/browser/)

Google Chrome has excellent developer tools that we will utilize when we get
into scraping websites.

[iTerm2](http://www.iterm2.com/)

An enhanced Terminal we'll learn to use.

## Install Dev Tools

In your terminal run this command (hold down command then press space, type in
terminal, then hit enter, a white or black screen should appear, where you want
to paste the line below, then press enter)

```
xcode-select --install
```

Then follow the instructions that pop-up

## Install Homebrew

Install Homebrew: Follow the instructions at [http://brew.sh/](http://brew.sh/). Scroll to the bottom of the page and paste the text that appears in your Terminal. Press return to execute the command. Text activity should indicate that Homebrew is being downloaded and installed. Follow any instructions that appear.

Update Hombrew: At the terminal, type the following command and press return:

```
brew update
```

## Configure Git

Set your global git user name and email. At the terminal, type the following two commands. Press enter after each one:

	git config --global user.name "Your Name"
	git config --global user.email your@email.address


## Install Node and Friends

Install Node.js: At the Terminal, type the following command and press return:

	brew install node


## Set up your SSH keys

SSH Keys are used to establish a secure connection to GitHub and Heroku.

Follow the instructions at GitHub to create and register new SSH keys: [Generating SSH Keys for GitHub](https://help.github.com/articles/generating-ssh-keys).

Nice work! You just set up your development environment and are already using the command line! This is serious stuff!
