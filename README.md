# YCTP Arduino

An attempt at recreating You Can Think Pad from Baldi's Basics game series using Arduino microcontroller

## Components
* An Arduino microcontroller (i used Nano, if you have other microcontroller the code might not work)
* LCD 16x2 w/ I2C interface bus
* 13 buttons (3x4 keypad + OK button)
* Addressable LED Strip (WS2812)

## Setup
  Connect everything as shown below:
  * Buttons:
    ![Buttons connection](/YCTP/img/buttons.png)
  * LED Strip:
    ![LED WS2812 connection](/YCTP/img/led.png)
  * LCD I2C display:
    ![LCD I2C connection](/YCTP/img/lcdi2c.png)

  * At the end, it should look something like this (or maybe a bit more cleaner than I did):
    ![whole circuit](/YCTP/img/main.png)

## Upload

In order to upload the code, you should first import all required libraries:

1. Download main branch as a ZIP file
2. Copy all folders in /libraries/ to your Arduino IDE libraries folder (usually located at C:\Users\\[user]\Documents\Arduino\libraries\)
3. Open YCTP.ino from /YCTP/
4. Upload code onto your microcontroller. [How-to](https://support.arduino.cc/hc/en-us/articles/4733418441116-Upload-a-sketch-in-Arduino-IDE)
5. All set!

## If you liked this project, don't forget to leave a star!
