-20-80-Battery-Charge-Percentage-Exceed-Signalizer-
LINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUXLINUX
Elegantly written venv-python alarm for 20-80% battery rule. It simply reminds you to plug-unplug the power cable to lengthten the battery life.  The programme starts as you login into your Linux user account..

Steps to reproduce
1. Create venv folder. Put the python script and alarm wav-file in there.
2. Create a bash script that changes directory and runs the py-file.
3. Add modifications to your .bashrc-file and a new crontab entry.  

Enjoy! LOL


There is some time lag in python power_plugged attribute status updating. Thus, some code refactoring and further sleeptime adjustments may be made, added or detalized.

CPU usage check:
ps aux --sort=-%mem | grep -i '[p]ython'
user 2300  0.0  0.0 256060 17720 pts/0    S+   04:21   0:00 python alert.py

Feel free to use, comment and play around with code!

P.S. I could't find any sort of such software. So, I wanted to created one on my own. It is a skill trainig soft written fast. Still it works! 

