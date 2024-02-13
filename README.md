# README

## Features
1. Login once, no need to do it again in your life unless you signout.
2. Easily log out of keepalive by pressing 'q' in the terminal. (This will help you to logout from the current session without keeping track of keepalive url.)
3. Sign out and log out of your username by pressing 'rq' in the terminal. (In case you want to change the username and password in the script)


## Simple Usage

### Note: Sign-out of the ISM authentication page before running this script###

#### For Windows
- Download `authenticator.exe` file and run it on your pc
- Enter the username (Your Adm. No.)
- Enter the password (You wont see password output on screen, just type the password and press enter)

#### For MAC/Linux
- Install Python3
- Run ```python authenticator.py```
- Enter username and password


### Errors:
- If you get output as
 ```
2024-02-13 19:45:01,832 - INFO - Exception |[WinError 10060] A connection attempt failed because the connected party did not properly respond after a period of time, or established connection failed because connected host has failed to respond| while trying to log in. Retrying in 5 seconds.
------------------------------------------------------------------------
Note: Sign-out of the ISM authentication page before running this script
------------------------------------------------------------------------
```
Then you will have to logout from the current login session. (Search for keepalive in your broswer and hit enter on the first link, You should get option to logout in that link.)

### Success:
- If you are not already logged-in and the credentials are correct then you will see output similar to
  `2024-02-11 22:32:43,348 - INFO - The auth location is: {Login URL}
2024-02-11 22:32:43,748 - INFO - The keep alive URL is: {KEEP ALIVE URL}
2024-02-11 22:32:43,750 - INFO - Sending request to keep alive.`


## New Features you can add:
- Convert script to exe file for Linux/MacOS and then inject this exe file in auto-startup of the device. (After that whenever you start your device this script will automatically start and no need to run this script manually.)
  
