# PCB Insulator

This project contains the design ideas to build a PCB insulator using UV LEDS.

The design is for a board of 100x75 mm, but you can compose several boards to increase the exposure surface. Just remember that you will need to use the appropriate power supply. I include some numbers to help with this.

# Numbers per board

LED specs: 3.3V 20mA

Voltage across resistor = 12V - (3 * 3.2V) = 2.4V

Resistor value = 2.4V / 0.02A = 120 Ohm

Power dissipated by resistor = 2.4V * 0.02A = 0.048 W = 48 mW

Power consumed by LED = 3.2V * 0.02A = 0.064W = 64mW

1 Board contains 16 resistors and 48 LEDs

Total power dissipated by resistors = 16 * 0.048W = 0.768W

Total power consumed by LEDs = 48 * 0.064W = 3.072W

**Total power = 0.768W + 3.072W = 3.84W**

**Total current consumption = 3.84W / 12V = 0.32A**

If you compose 4 boards you would need a power supply supporting 15.36W and 1.28A


# References

I have based my design on those other projects:

- http://www.instructables.com/id/Arduino-controlled-UV-LED-PCB-Exposure-Box/?ALLSTEPS
- http://www.carlolog.net/log/2012/09/making-an-uv-exposure-box-from-scratch/
- http://www.electronics-lab.com/project/led-uv-exposure-box/

# Part list

- [LEDs UV](https://www.amazon.es/gp/product/B01ANW9ZX2/ref=ox_sc_act_title_2?ie=UTF8&psc=1&smid=A1DMSD13LMYETC).
- [Power supply](https://www.amazon.es/gp/product/B01GC5QQ1I/ref=oh_aui_detailpage_o00_s01?ie=UTF8&psc=1)
- 100x75mm single layer PCB
- 120 Ohm 1/4W resistors

# Photos

https://goo.gl/photos/k7TKoiVqc2WFZSGJ9
