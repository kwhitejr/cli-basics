# CLI Basics

## Basic Commands
Let's read about a couple of the most common commands that you're going to use.

`ls` = "list directory"; lists all files and folders in the present working directory (where you currently are).

`pwd` = "present working directory"; tells you where you currently are!

`cd foldername` = "change directory"; switches to the directory named 'foldername'. 'foldername' is always a child of the __pwd__ (present working directory). 

`cd ..` =  changes directory to parent of __pwd__. 

`cd ~` = changes directory to user's home directory. Very useful for resetting if you get lost!

`mkdir foldername` = "make directory"; creates a directory named 'foldername'. When you make directory this way, the new 'foldername' directory will be located inside of the __pwd__.

`touch filename.ext` = create a new file of name 'filename' and type '.ext'.

## Step One: Try It Out!
The best way to learn the command line is to __use the command line__! Let's practice a bit to get you settled. First, open your terminal (iTerm2 if you use a Mac or GitBash if you use a Windows PC). Use the `pwd` command to determine your present working directory.

Our first goal is create a `DevLeague` folder on your desktop using the command line. First you need to navigate to the desktop from the command line. Typically there is a "desktop" or "Desktop" folder in user's home directory (__remember__: in command line, capitalization and spelling matters a lot!). Navigate to the user's home directory using `cd ~` and then use `ls` to check for a desktop folder. When you find it, navigate into it using the appropriate `cd` command.

As a general rule, it is a good idea to use `ls` command whenever you enter a new directory so that you can see what you're working with. From inside of your desktop directory, use `ls` to see what is on your desktop. Clean as a whistle or got a lot of junk?

Spoiler: !> This is a spoiler.

## Setup

Fork and clone this repository!