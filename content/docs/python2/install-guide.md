---
Title: Installation Guide
weight: 2
---

# Python Installation Guide

## Mac

1. visit [https://www.python.org/downloads/](https://www.python.org/downloads/)  
2. click on “Download Python 3.14.x”  
3. it should download a file titled “python-3.14.5-macos11.pkg”  
4. press continue all the way, allowing any permissions if necessary

## Windows

1. visit [https://www.python.org/downloads/](https://www.python.org/downloads/)  
2. click on “Download Python install manager”  
3. it should download a file titled “python-manager-26.2.msix”  
4. your computer may warn you that it is an executable, just press “OK” to launch  
5. say Y to “Install the current latest version of CPython”  
6. say Y to “Add Python to Command Line” or anything similar  
7. it should now say installing and extracting  
8. after its done, it prompts “View online help?” \- answer N

## Ubuntu / Debian / Linux Mint

1. enter the shell  
2. sudo apt update  
3. sudo apt install python3 python3-pip python3-venv \-y

## Fedora / RHEL / CentOS

1. enter the shell  
2. sudo dnf install python3 python3-pip

*NOTE: for older CentOS versions, run    sudo yum install python3 python3-pip    instead*

## Arch Linux

1. enter the shell  
2. sudo pacman \-Syu python python-pip

## \=== AFTER INSTALLATION \===

1. verify python is installed by entering “python3 \--version” in the terminal  
2. verify pip is installed by entering “pip3 \--version” in the terminal

*NOTE: for linux users, if the default package manager only offers older versions of Python and you wish to get the latest build, you can pull newer, pre-compiled versions through the Deadsnakes PPA Team Repository, though this will not be necessary.*

# OOP Installation Guide

1. there is nothing to install, OOP comes default with Python installations

if theres any issues with any of the above steps, ping @annie110100 ( uid: 821634430070161409 ) in the bbcs discord before the conference