## Adafruit PAM8302 Mono Amplifier PCB
<a href="http://www.adafruit.com/products/2130"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

This super small mono amplifier is surprisingly powerful - able to deliver up to 2.5 Watts into 4-8 ohm impedance speakers. Inside the miniature chip is a class D controller, able to run from 2.0V-5.5VDC. Since the amp is a class D, its very efficient (over 90% efficient when driving an 8Ω speaker at over half a Watt) - making it perfect for portable and battery-powered projects. It has built in thermal and over-current protection but we could barely tell it got hot. There's even a volume trim pot so you can adjust the volume on the board down from the default 24dB gain. This board is a welcome upgrade to basic "LM386" amps!

The A+ and A- inputs of the amplifier go through 1.0uF capacitors, so they are fully 'differential' - if you don't have differential outputs, simply tie the Audio- pin  to ground. The output is "Bridge Tied" - that means the output pins connect directly to the speaker pins, no connection to ground. The output is a high frequency 250KHz square wave PWM that is then 'averaged out' by the speaker coil - the high frequencies are not heard. All the above means that you can't connect the output into another amplifier, it should drive the speakers directly.

Comes with a fully assembled and tested breakout board. We also include header to plug it into a breadboard and a 3.5mm screw-terminal blocks so you can easily attach/detach your speaker.

These are the Eagle CAD files for the Adafruit PAM8302 Mono Amplifier

For more details, check out the product page at

-----> https://www.adafruit.com/products/2130

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

All text above must be included in any redistribution

Designed by Limor Fried/Ladyada for Adafruit Industries.
Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional information.
