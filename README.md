# IOB-I2C-PCA-9685-PWM
## License: CERN Open Hardware Licence v1.2

IOB I2C PCA9685 PWN driver

 * The PCA9685 is an i2c-controlled PWM driver with a built in free running clock.
 * The board is 5V compliant, which means you can control it from a 3.3V microcontroller and still safely drive up to 6V outputs (for LEDS and Servos)
 * 6 address select pins support up to 62 of these on a single I2C bus
 * Adjustable frequency PWM up to about 1.6 KHz
 * 12-bit resolution for each output
 * Configurable push-pull or open-drain output
 * Output enable pin to quickly disable all the outputs

