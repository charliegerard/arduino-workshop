# Arduino workshop

## Goal:

![goal](https://s-media-cache-ak0.pinimg.com/originals/65/5b/40/655b402f7ff54d14a4ada329d6c994fd.gif)

---

## Material:

* Arduino Uno

<img src="./images/arduino.png" width="150" />

* Breadboard

<img src="./images/breadboard.png" width="150">

* Neopixel RGB v2

<img src="./images/flora.jpg" width="150">

* Photocell (light sensor)

<img src="./images/photocell.png" width="150">

* Resistor

<img src="./images/resistor.png" width="150">

* Jumper wires

<img src="./images/jumper-wires.png" width="150">

* Aligator clips

<img src="./images/clips.png" width="150">

---

## Wiring the circuit:

![schematics](workshop_2.png)

---


### Test your circuit

* Download the [Arduino IDE](https://www.arduino.cc/en/Main/Software)
* Install the Adafruit Neopixel library:
  * Open the Arduino IDE.
  * In the menu bar: `Sketch > Include Library > Manage Libraries` and enter "Adafruit Neopixel".
  <img src="./images/library.png" width="400">

  * You may have to close and re-open the IDE after installation.
* `File > Examples > Adafruit Neopixel > strandtest`
* Check that your board is selected in `Tools > Board` and `Tools > Port`
* Click on the upload button and the Neopixel should light up
* Upload the custom sketch `workshop.ino`
* Turn on mobile phone's flashlight and point it to the photocell - the Neopixel should light up.
* Try chaining everyone's circuits to see if it works.

### Next steps

* Custom circuit with ATTiny chips


