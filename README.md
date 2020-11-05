# edf-box

This is a somewhat ambitious proposal to build a "universal box" which can serve (with appropriate firmware) as a small laboratory instrument for control and data acquisition applications.  It is in some sense an answer to various pieces of junk produced by NI and others.  It is not intended to be particularly high-precision or high-speed, just to provide honest 12-bit performance and a simple control panel.

Here are some of the proposed features:

* ATMega328 microcontroller.  Not fancy, but can easily be understood and programmed using the Arduino environment and unlikely to go obsolete any time soon
* Several robust splash-proof pushbutton switches
* 16x2 backlit LCD display
* Knob with rotary encoder and push switch
* Several channels of 12-bit DAC and ADC with provision on board for signal conditioning
* MOSFET switch outputs for high power / high voltage loads
* USB/Serial interface

Some construction notes:

* Mount in a Hammond transparent box, with LCD under the lid and buttons, knob through round holes
* Power, USB and I/O connectors along one board edge for easy access through slot in box side
* Use an external power brick with regulators on board.
