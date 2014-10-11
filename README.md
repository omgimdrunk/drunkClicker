drunkClicker
============

Clicker Heroes auto clicker w/ buff timer
This script makes some initial assumptions,

1) You already have the Vaagur ancient and it is at MAX
The timing of the buffs is based off of this.
If not; you can still use this script with out the buffs by just using [-c X,Y]

2) You have all the available buffs from your adventures.
Not necessary for it to work but I am just assuming.

3) You are using Windows - this is a must, no way around it.
to use:
- install python 3.x ( I used 3.4 )

- install the win32api for python - http://sourceforge.net/projects/pywin32/files/pywin32/

- from cmd, cd to the location of drunkCLicker.py

- type python drunkClicker.py [-t x,y] to test where the mouse will move to on your screen.
eg: [python drunkCLicker.py -t 1700,600]
position this so that the mouse lands on top of the monster.

- Once mouse position is confirmed -c x,y or -bc x,y can be used to start the clicking.
eg: [python drunkClicker.py -c 1700,600] this will perform just mouse clicks.
eg: [python drunkCLicker.py -bc 1700,600] This will perform mouse clicks with DR Ceremony.

4) This script may be CPU intensive to older systems. May cause lag.
As a fail safe, moving the mouse will end this script.

5) If you experience system unresponsiveness,
you can adjust the User Defined Variables below.
