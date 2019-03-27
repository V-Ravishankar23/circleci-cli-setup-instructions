# CircleCI CLI Setup
How to set up the CircleCI CLI on OSX from scratch using Homebrew

## Installing Homebrew
Homebrew is a package manger for OSX that lets you quickly install lots of different applications and command line tools. It's worth having this installed anyways, and it makes it easy to get the CircleCI CLI installed. You can read more on it [here](https://brew.sh/).

To install Homebrew, open Terminal (you can press `CMD` + `Spacebar`, type "Terminal" and hit enter to quickly open it) and paste the following:
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
This script will explain what it does and then pause. Continue running the script to install Homebrew.

## Using Homebrew to install the CircleCI CLI
Once Homebrew finishes installing, type the following into the Terminal prompt and press `Enter`:
```
brew install circleci
```
