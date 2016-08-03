This sample app shows how to connect with [mosquitto](https://pypi.python.org/pypi/mosquitto/) to [CloudMQTT](http://www.cloudmqtt.com) and both publish and subscribe messages. 

    $ pip install -r requirements.txt

I got the definitions from this page.
https://pypi.python.org/pypi/paho-mqtt/0.9

This was tested against cloudmqtt.com 

https://api.cloudmqtt.com/sso/cloudmqtt/websocket

The code sends a publish message to the Cloud, and also subscribes to messages.
Example of a subscribed message is On or Off.
Library for wiring Pi is included and Pin 17 is configured to send a On or Off message to the 
Rpi Pins.

Connect a 220 ohm resistor and a LED to Pin 17, and GND pin appropriately.

