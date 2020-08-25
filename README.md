Usage: The dab object takes five parameters. The first three will be the length of each timer. 
The first is a cortesy timer for the user to get their torch ready. 
The second is the amount of time the user plans to heat up their nail for. 
The third one is the amount of time the user wishes to wait. 
Time is in seconds and a mathematical expression which evaluates 
to an int or float is acceptable for any of these three. 
The fourth is the interval the timer increases by. Default is 1 which would go down one second at a time. 
It should be <= 1 and smaller values provide greater frequency of ticking. 
The last is simply the number of digits after the decimal place the user wants for the formatted time. 
This is by default set to zero but should be increased to some larger int if increment < 1. 
The last line shows proper usage for a user who wants ten seconds to get their torch ready, 
sixty seconds heating their nail, and ninety seconds waiting for it to cool down.
In DabTimer.py the last line must be changed manually by the user in order to change the time.
Furthermore, this line can be removed and it can be called somewhere else after importing the module.
dt.py takes these paramaters as command line arguments and should be used on the command line 
to increase efficency by never editing a file. 
The default for dt when no paramaters are given are (10, 60, 90). 
To change this simply edit the last block of the conditional at the bottom of the file (line 46). 
