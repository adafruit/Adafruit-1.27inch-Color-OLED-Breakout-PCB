# PCB files for Adafruit 1.27" Color OLED Display Breakout

<a href="http://www.adafruit.com/products/1673"><img src="assets/image.jpg?raw=true" width="500px"><br/>Click here to purchase one from the Adafruit shop</a>

We love our black and white monochrome displays but we also like to dabble with some color now and then. Our 1.27" color OLED displays are perfect when you need a small display with vivid, high-contrast 16-bit color. The visible portion of the OLED measures 1.27" diagonal and contains 128x96 RGB pixels, each one made of red, green and blue OLEDs. Each pixel can be set with 16-bits of resolution for a large range of colors. Because the display uses OLEDs, there is no backlight, and the contrast is very high (black is really black). We picked this display for its excellent color, this is the nicest mini OLED we could find!

This OLED uses the SSD1351 driver chip, which manages the display. You can talk to the driver chip using 4-wire write-only SPI (clock, data, chip select, data/command and an optional reset pin). Included on the fully assembled breakout is the OLED display and a small boost converter (required for providing 12V to the OLED) and a microSD card holder. This design includes built-in logic level shifting so you can use it with 3-5VDC power and logic levels. Our example code shows how to read a bitmap from the uSD card and display it all via SPI.

Of course, we wouldn't just leave you with a datasheet and a "good luck!" - [we've written a full open source graphics library that can draw pixels, lines, rectangles, circles, text and bitmaps as well as example code](https://github.com/adafruit/Adafruit-SSD1351-library). The code is written for Arduino but can be easily ported to your favorite microcontroller. [Check out the tutorial we have for both this and the 1.5" version of the OLED for wiring diagram, code, and more!](https://learn.adafruit.com/adafruit-1-5-color-oled-breakout-board/).

## License

Adafruit invests time and resources providing this open source design, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Designed by Adafruit Industries.  
Creative Commons Attribution, Share-Alike license, check license.txt for more information
All text above must be included in any redistribution
