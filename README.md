The script randomly selects an image from a folder and shows it on the Pimoroni inky what display. 
A cronjob can be set up so that a new image is displayed every x (e.g., 5) minutes: 
In the terminal type crontab -e 
and add 
*/5 * * * * /usr/bin/python path/to/script/display.py
Note: Please inspect line 11 and line 12 in display.py
