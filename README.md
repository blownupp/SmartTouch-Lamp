# SmartTouch-Lamp
WIP: Touch sensitive, web connected, RGBW lamp for staying in touch with your family!

As this is a work in progress, there is a lot of work to be done! I will be using this repository as sort of a learning experience,
both to familiarize myself with git and to develope some good habits with documentation and version control/tracking!

The idea for the lamp is that each user with a lamp will be able to set their own color, so that when they touch their lamp
it will light up with their color and the other lamps in the Family will sync up with that color, allowing you to let your family
know that you're thinking about them without calling or texting across any number of miles all thanks to the internet!

The intended platform will be the Photon and the Particle IDE, with a simple circuit consisting of 10-20 WS2812B LED's OR 3 * 3w
RGB LED's with an additional 1-3w White LED - if time permits (This is a holiday present afterall!).
The touch circuit will be conductive paint on the inside of the frosted lamp shade, hooked to A0 on the Photon from 5v through a
1M0 resistor; sudden change in the average current reading on A0 indicating a touch event.

As I put more work into this project I will be attempting to use this repository to organize the various .cpp/.ino/.h files,
SketchUp models and so on.
