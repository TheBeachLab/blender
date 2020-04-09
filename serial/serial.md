# Serial communication in Blender

## First steps

With an Arduino or similar sending some data over the serial port, open a python console in Blender and try:

```python
import serial
arduino = serial.Serial('/dev/ttyUSB0', 9600)
arduino.readline()
```

Adjust till you get data and move to next step.


