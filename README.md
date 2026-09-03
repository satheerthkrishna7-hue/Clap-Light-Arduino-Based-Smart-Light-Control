Clap Light – Arduino-Based Smart Light Control


VEDIO LINK
https://github.com/satheerthkrishna7-hue/Clap-Light-Arduino-Based-Smart-Light-Control/issues/1#issue-5339144428

A simple Arduino-based smart lighting system that uses a KY-038 sound sensor to detect a double clap and control a light through a relay module. The Arduino UNO processes the clap signals and switches the relay ON or OFF, allowing the light to be controlled without a physical switch.

Components Used

- Arduino UNO
- KY-038 Sound Sensor
- 1-Channel Relay Module
- Light/Lamp
- Jumper Wires

 Working

The KY-038 detects the sound of a clap and sends a digital signal to the Arduino UNO. The Arduino measures the time between two detected claps. If two claps occur within the specified time interval, the Arduino changes the state of the relay, which turns the connected light ON or OFF.

 Features

- Double-clap detection
- Relay-based light switching
- Simple and low-cost design
- Arduino-based control
- Uses timing and debounce logic to reduce false triggers

 Concepts Learned

- Digital input/output
- "digitalRead()" and "digitalWrite()"
- Relay control
- Sound sensor interfacing
- Timing using "millis()"
- Debouncing and signal detection
