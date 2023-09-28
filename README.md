# Python Udp 2 vJoy

This script allows to listen to udp in aim to simulate joystick with vJoy.  

To use this script you need Python install on your device and vJoy.  
- https://www.python.org/downloads/  
- https://github.com/shauleiz/vJoy/releases/tag/v2.1.8.39  

The official vJoy driver installer don't work for me to I am using this one:  
- https://softradar.com/vjoy/download/de/

```
Default port: 2520
1|B|1        # Set joystick 1 button 1 to true
1|b|1        # Set joystick 1 button 1 to false
2|A|0|-0.5   # Set joystick 2 axis 0 to -0.5
2|A|x|0.5    # Set joystick 2 axis x to 0.5
```
       
          
