# README

## Simple Usage

### Note: Sign-out of the ISM authentication page before running this script###

- Download `authenticator.exe` file and run it on your pc
- Enter the username (Your Adm. No.)
- Enter the password (You wont see password output on screen, just type the password and press enter)
- You should get the output `Logging to the firewall...`
- If you are not already logged-in and the credentials are correct then you will see output similar to
  `2024-02-11 22:32:43,348 - INFO - The auth location is: {Login URL}
2024-02-11 22:32:43,748 - INFO - The keep alive URL is: {KEEP ALIVE URL}
2024-02-11 22:32:43,750 - INFO - Sending request to keep alive.`
- If you get the above output that means you are successfully logged-in and until the script is running you will not need to sign in again
- If you close the script it will auto logout.
