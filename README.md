# OSX-Keylogger


### Installation

**Requires Python 2.7**

This keylogger requires some dependencies from other sources.

Install [PyObjC](http://pythonhosted.org/pyobjc/install.html) from this website in order for the app to work. I had to perform a manual installation, which is featured lower down on the website.

If you are using IDLE, follow these instructions. I am unaware of the requirements for other Python IDEs.

Since System Preferences is stupid, you must add IDLE to the Accessibility pane in the Security page.

Go to System Preferences, Security & Privacy, Privacy, Accessibility, then add basically all of the apps in your Python folder. I added IDLE, Python Launcher, and Build Applet. I'm not sure which are required since I am lazy, just do it. Also everytime you run it, IDLE will get unchecked from the pane so you will have to check it again. Although it might just be me. Who knows.

### Usage

In the actual python file, replace the given path with where you want the log file to be saved.

Remember to add IDLE to the security pane in System Preferences each time. My apologies, I am working on a fix for that. However, the script should keep running if you close your laptop, so this should not happen often.