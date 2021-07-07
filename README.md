# Keyloggers
Keyloggers are programs that give hackers access to our personal data as these are activity-monitoring software.
In one work keyloggers are the programs to capture the key strokes of our computer.
They keep logs of everything we press on the keyboard like any password, credit card number. Despite of that it can be useful as well.

I have made a keylogger which is a basic one with not much functionality as the ones available in market now.
It will capture all keystrokes and saves them in a file named "keylogger.txt".
Then it will send the contents of the file to the given email address.
I did not make it executable so it has to be explicitely called.
**You will need to pynput, smtplib and ssl installed first**
SYNTAX: python keylog.py
Python comes with the library smtplib and ssl preinstalled.
Install pynput with: pip install pynput
You need to press ctrl key to exit out the keylogger.

