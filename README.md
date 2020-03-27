# Device-Work-Detect
Device Work  Detect
In this project,
we detect to electrical devices. Usually using oven,microvawe oven,kettle etc. devices in kitchen. 
when these devices works over, you can forget this.for this reason you need a reminder.
This project measure to devices current. When devices is over current=0, when devices is working current = 20,30A etc. 
In this way, the transmitter sends the sensor value to the receiver(nRF24L01).
If the sensor value bigger than referans value, device is working, else device is over. 
Receiver check to value. If device work is over,through led and buzzer blink.
