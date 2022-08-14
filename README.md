# Hue Helper

Hue Helper is an augmented reality (AR) application that interacts with a user's view of the real world in order to provide two main features:
  1. Color correction for those who are color blind, and 
  2. Color-blind simulations for those with typical color vision

**Insert GIF here**

[Click here to learn more about this project!](https://devpost.com/software/a-ja3nou)

## Color correction

Hue Helper provides color correction for the three most common forms of color blindness:
  * __Protanomaly/protanopia__ (insensitivity to red light)
  * __Deuteranomaly/deuteranopia__ (insensitivity to green light)
  * __Tritanomaly/tritanopia__ (insensitivity to blue light)

Although the application cannot fully simulate normal color vision for those who are color-blind, it can help them differentiate between colors in a way that they would not normally be able to.

This feature can help color-blind people perform everyday tasks that many with normal color vision take for granted. Some examples include:
* Distinguishing between raw and cooked meat
* Distinguishing between ripe and unripe fruit
* Putting together a matching outfit
* Reading pie charts or other diagrams that rely on color

## Color-blind simulations

Hue Helper also provides simulations of __protanopia__ (red-blindness) and __deuteranopia__ (green-blindness).

These simulations allow those with normal color vision to experience color blindness, which is extremely helpful for creating and testing products that are accessible to color-blind people.

## Technologies used

* The application was developed using [Spark AR Studio](https://sparkar.facebook.com/ar-studio/).
* Color lookup tables were created to provide the application with the appropriate parameters for color transformation. These lookup tables were created using [Adobe Photoshop Lightroom](https://www.adobe.com/products/photoshop-lightroom.html).

## Acknowledgements

* [Alano Peirce]() created all of the color lookup tables and performed the associated mathematical calculations necessary for converting between color spaces.
* [Saori Hunziker](https://devpost.com/pinkokinawa84) developed the user interface and linked it to the back end of the application (a.k.a. the color lookup tables).
