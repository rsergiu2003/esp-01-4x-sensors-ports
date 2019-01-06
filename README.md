![board image](https://github.com/rsergiu2003/esp-01-4x-sensors-ports/raw/master/board.png)

![sketch image](https://github.com/rsergiu2003/esp-01-4x-sensors-ports/raw/master/sketch.png)

# PCB for esp-01, with 4 sensors headers
A simple pcb on which you can connect 4 sensors to the 4 gpio pins, also it has a voltage stabilizer which can take up to 30V (so you can safely power it up from 5,12,24V source)

The board has 4 pin headers (3 pins) with Signal, 3.3v, GND, each signal is connected to a GPIO pin (0,1,2,3) of the esp-01, so they can be used for reading sensors values.

## Features
  - each pin has a pull up resistor
  - 3.3 Voltage stabilizer
  - capacitor for voltage fluctuations
  - power indicator LED
  
## Testing
The board was tested with DHT22, DHT11, DS18B20, but is should work with any digital sensor working on 3.3V.

## Software
Here are some repositories you can check out for using with this board.

## 3D Model
You can see the fusion360 model here : https://a360.co/2FeM3dN you can download it and test it in your own context if you have to, this is very usefull if you want to use it in a box, or just to see how it looks in real life.

## More info
If you want more info feel free to leave me a message !
