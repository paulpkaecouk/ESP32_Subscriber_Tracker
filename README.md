# ESP32_Subscriber_Tracker
Using Elecrow ESP32 3.5" HMI device for a Clock, Temp gauge &amp; YouTube Subscriber monitor. 

  Written for use with Elecrow ESP32 3.5 Inch OLED Touch Screen.

  Use Board type:- ESP32 Dev Module
  Display Driver Chip = ILI9488
  Pixels 320 x 480

Libraries
---------
PKAE_Timer  : A very basic timer variable handler to simplify my code.
TFT_eSPI    : Control the 3.5" (320 x 480) display. 
YoutubeApi  : Obtain Youtube statistics data such as number of Subscribers, Views and Quantity of Videos.
JPEGDecoder : Fascilitate displaying JPEG image file read from the onboard SD card reader.
SD          : Enavbles Reading and Writing from/to SD Cards. Used to read a JPG file to display on the LCD.

Sketch Header Files
Credentials.h  : Hold your WiFi, YouTube and NTP Server credentials
Logo.h         : Defines long numeric arrays used to store various icons and my logo. (create your own using Rink Dink website)  

