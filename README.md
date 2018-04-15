# TinyBoard84100

Tiny beakout board for the ATtiny841 (or any other 14 pin
AVR) with AVR ISP programming header, voltage regulated and
with reset button.

It is programmable with the Arduino IDE with the ATtiny
library addon thingy. Or a proper toolchain for all the
tryhard nerds out there :)

Designed in KiCAD open-source and possibly for sale on Tindie
somewhere in the future. No promisses.

It's actually a second version of the design, first was not
published nor tested. It was designed, manufactured and forgoten about.

If you're experienced and want to tell me how wrong I did
everything, feel free to PM me. I'm open to your feedback.

Q: What's so special about the ATtiny841?

A: Compared to ATtiny84, the ATtiny841 has one extra 16-bit
timer with two PWM channels, one more
ADC, more input channels, one extra comparator, one extra USART.
And for more details go check Microchip's product site.
If you want to build it yourself, ATtiny84 seem to be pin compatible
so you should be just fine using that if you want to shave off
few cents and/or don't need the extra functionality of 841.
