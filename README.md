# Kali-Patch-Script
Created a simple Bash Script to auto update Kali Linux VM

Steps taken to successfully execute a simple Bash Script created to patch and update a Kali box:
1. Open terminal in Kali
2. executed sudo su for super user privs: enter kali password to gain root commands
3. ran "nano (enter Script Name)"
4. A nano text opens for scripting: the first line will display: 

#!/bin/bash

echo "Please wait, I'm patching myself"

sudo apt update; sudo apt upgrade -y; sudo apt dist-upgrade -y; sudo apt autoremote -y

5. Save script as .sh
6. Test script in terminal as "Bash (Script name .sh)"
7. This script will execute the text "Please wait, I'm patching myself" and launch the commands necessary for upgrading and patching the Kali Linux OS.
