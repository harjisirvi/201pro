Folder Monitor is a program for Windows 10 & Windows 11 written in Python 3.11 for monitoring a local folder (I haven't tried with network folders). Folder Monitor will wait for all files in a copy session to be copied then display a Windows Toast notification.
This is a very simple program that I wrote because I needed it. The code is by no means organized or standardized, but it works.
Basically the program uses the "watchdog" library to monitor the appearance of new files in the monitored folder. It waits for all files to be copied and then displays a Toast Notification.
I specified earlier that it is written in Python 3.11 because Python 3.12 was released at the time, but Windows Toast does not run with - I think it has something to do with the watchdog module.