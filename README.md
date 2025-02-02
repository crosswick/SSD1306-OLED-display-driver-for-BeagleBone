# SSD1306-OLED-display-driver-for-BeagleBone
This is a SSD1306 OLED Display Library fully compatible with the BeagleBone. This fork is a work-in-progress tailored to a Bela Original or Bela Mini system that need to use the i2c-1 port.

The Library has 3 components:
1. I2C component for enabling communication between the BeagleBone and display.
2. Control component for sending I2C commands to configure and control the display.
3. Graphics component for drawing geometrical figures, bitmaps, texts, characters, emoticons and numbers.

Written by: Vinay Divakar

Website: www.deeplyembedded.org

Youtube: https://youtu.be/sDKf6zW6Pyg

MIT license, check LICENSE file for more information

Hardware connections are as shown below link:

Blog Post: https://deeplyembedded.org/ssd1306-oled-driver-beaglebone/


This Library is written in C. To use it, just include the I2C and SSD1306 Libraries in your project.
