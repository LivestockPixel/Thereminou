# How to build your own Thereminou

Thereminou is inspirated by the famous electronic instrument : **The Theremnin**. You'll find here all the sources to build your own **audio-reactive cyber-cat**.
Thereminou is a really lightweight device that can send MIDI message throw a Wifi network (with RTPmidi).
This controler is based on 2 ultrasonic sensors that read the distance between your hand and the box, then send MIDI control message based on this distance value.

##Required Components:
- ESP8266 Board
- HC-SR04 Ultrasonic Sensor x2
- Breadboard
- Basic LED 5mm x2
- 220 Ohm Resistor x1
- Breadboard Jumper Wires

##Required Software:
- [Arduino IDE](https://docs.arduino.cc/software/ide/#ide-v2)
- [RTPmidi](https://www.tobias-erichsen.de/software/rtpmidi.html)

##Circuit Diagram:
![alt text](Thereminou_circuit diagram.jpg)

##Setup
Open the Arduino IDE code editor. Open the *ESP8266_theremin118.ino* file.
Install all the dependencies. Load the program on your board.

##To go further
Thereminou could also send Midi message directly via USB (if your board support it natively, like Arduino Leonardo or Teensy ).
Check your board here : [MIDI over USB board](https://tttapa.github.io/Control-Surface-doc/Doxygen/d8/d4a/md_pages_MIDI-over-USB.html)
Otherwise you can use Hairless to get your MIDI message via serial : [Hairless MIDI Bridge](https://projectgus.github.io/hairless-midiserial/)

Many thanks to Gurbrinder Grewal, Derek Pritchett and Bryne Carruthers for their work : [Arduino Theremin](https://www.arduinotheremin.com/)

