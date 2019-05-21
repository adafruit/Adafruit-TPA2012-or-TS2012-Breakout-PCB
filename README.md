## Adafruit TPA2012 or TS2012 Breakout PCB
<a href="http://www.adafruit.com/products/1552"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

This incredibly small stereo amplifier is surprisingly powerful - able to deliver 2 x 2.1W channels into 4 ohm impedance speakers (@ 10% THD). Inside the miniature chip is a class D controller, able to run from 2.7V-5.5VDC. Since the amp is a class D, it's incredibly efficient (89% efficient when driving an 8Ω speaker at 1.5 Watt) - making it perfect for portable and battery-powered projects. It has built in thermal and over-current protection but we could barely tell it got hot. This board is a welcome upgrade to basic "LM386" amps!

The inputs of the amplifier go through 1.0uF capacitors, so they are fully 'differential' - if you don't have differential outputs, simply tie the R- and L- to ground. The outputs are "Bridge Tied" - that means they connect directly to the outputs, no connection to ground. The output is a ~300KHz square wave PWM that is then 'averaged out' by the speaker coil - the high frequencies are not heard. All the above means that you can't connect the output into another amplifier, it should drive the speakers directly.

Comes with a fully assembled and tested breakout board with 1.0uF input capacitors. We also include a dual mini DIP switch for setting the amplifier gain on the fly, 3.5mm screw-terminal blocks so you can easily attach/detach your speakers, and some header in case you want to plug it into a breadboard. You will be ready to rock in 15 minutes!

PCB files for the Adafruit TPA2012 or TS2012 Stereo Class-D Audio Amp Breakout. The format is EagleCAD schematic and board layout
- https://www.adafruit.com/product/1552

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

All text above must be included in any redistribution

Designed by Limor Fried/Ladyada for Adafruit Industries.
Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional information.
