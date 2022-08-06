# Smart Dorm

For our final project in 6.08 (Intro. to EECS via Interconnected Embedded Systems), we have designed and implemented three modules that serve to ‘smartify’ students’ dorm rooms. In addition to servicing the IoT and electronics side, we have also tried to expand our reach by incorporating dynamic mechanisms, a mobile app for user interfacing, and 3D printing enclosures in an attempt to replicate what a final product on the market could look like.

The first module we introduce in this write-up is the knock-detection and camera module. When a person knocks on a user’s door, a picture of them is taken, processed onto the server, and is sent to the app. We illustrate in the demo video one of many scenarios where this could be useful.

Next is the door lock module. The idea is that by bringing the door handle of the door down just enough with the servo, people on the other side can come through when the door is by default in a locked state. This is one of two modules with mechanical capabilities.

Our last module is the one responsible for toggling both the light switch in a room and a connected RGB LED strip. It switches a light switch on and off using a compliant mechanism which we 3D printed at the Cypress Engineering Design Studio. By interfacing with the server via the app, users are able to set specific RGB values or select a preprogrammed light sequence. 

Last but not least, the app is vital in bringing all the modules together under one interface. Written in ReactNative, the app is meant to make the smart dorm modules an extension of a user’s pre-existing IoT environments by making it accessible on their phones.

The demo to our final project is located here: https://www.youtube.com/watch?v=HCM5IS-3c3I
