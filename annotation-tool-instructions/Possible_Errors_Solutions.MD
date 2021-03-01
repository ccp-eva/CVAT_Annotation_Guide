# CVAT Annotation Tool - User’s Manual

Anam Zahra, Manuel Bohn

January 2021


When using CVAT, you might come across several errors. We keep track of the errors faced and their solutions in order to nit fall back on same thing again and again. It'll also help users in future.

## Opening in existing browser session error
In this situation, when you type *google-chrome* in terminal, no window pops up and 'Opening in existing browser' statement appears in terminal.

### Solution
Solution is simple, just type the following command ```pkill chromium```. Type *google-chrome* again and you are good to go.
If this also doesn't work type ```pkill chrome``` and then *google-chrome* should work.


##  Can't find a suitable configuration file in this directory or any parent. Are you in the right directory.
You possibly are not in the cvat directory.

### Solution
Solution is simple, change directory using following command `cd /opt/cvat`. Try your command that was causing error again and it ll work.
