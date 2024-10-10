# -Arduino_Code

Steps to Run the Code
Install the DHT Sensor Library:

Open the Arduino IDE.
Go to Sketch > Include Library > Manage Libraries.
Search for "DHT sensor library" by Adafruit and install it.
Wire the Components:

Connect the DHT11 sensor:
VCC to 5V on the Arduino.
GND to GND on the Arduino.
Data pin to digital pin 2 on the Arduino.
Place a 10k ohm resistor between VCC and the data pin.
Upload the Code:

Copy the code above into a new Arduino sketch.
Connect your Arduino to your computer and select the correct board and port in the Arduino IDE.
Click on the upload button.
Open the Serial Monitor:

After uploading, open the Serial Monitor from Tools > Serial Monitor (or press Ctrl+Shift+M).
Set the baud rate to 9600.
Expected Output
You should see humidity and temperature readings printed every 2 seconds. If the sensor fails to read, it will notify you in the Serial Monitor.
