# Remocon
Low cost RF controller and receiver(s) based around STM32 and Arduino with flexibility in mind.
# Overview
This is an alternative RF System for hobbists which has flexibility in mind. It mainly consists of a remote controller and a receiver, both powered by the STM32F103 (Blue Pill). Thanks to this hardware yo can easily get 15 PWM channels to drive traditional stuff like servos and ESCs. Additionally, you can configure GPIO pins as you please in order to toggle leds, enable dc motors etc. Other things like SPI,I2C and CAN are suported.

For now this controller only can otput PWM signals through the use of the Servo library, or the analog write function, but feel free to write your own PPM  or other method for communication with your devices.

The main board for the remote features an array of Dip switches that bypass the onboard inputs, so you can connect your own inputs, sensors, etc.
# Requirements
+Roger Clark's Arduino STM32 core
+Adafruit GFX and SSD1806 Libraries

# Known Issues
# Improvements
