# KuhlKuh
Use Windows Hello to authenticate yourself for KeePass


Licensed under GPL v3 <br />
Beta Version 1.3 <br />
Idea by Alexander Da Silva Sebö <br />
Programming by Sabir Ahmed

Welcome to KuhlKuh, a small program that was written so that Windows Hello could be used for authentication to send the master password to KeePass.

1) At first launch, authenticate yourself with Windows Hello. Type your KeePass master password in the corresponding field. Enter the exact window name in the corresponding field. 
You can chose if you want the program to launch at start up. At the moment, this might freeze the program for some seconds.
You can lock the window once the data was put in.
2) Whenever, the KeePass password window is active, go to your windows tray, right click on the sunglass and chose “sign in”. The program will then search for the window title you configured and, if found, enter the master password for you.
3) Every time you want the program to send the master password you need to sign in first. This is to prevent miss use.

If you find errors in this program feel free to report them under issues. Feel also free to contribute to this project if you like.
