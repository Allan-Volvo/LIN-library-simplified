# LIN-library-simplified
A bundled and easily usable library for use with ESP32 to send, recieve and handle message LIN communication layouts. Can be used with switchpacks and other units which talks using LIN.

The project will be updated later on.

The LIN message layout is based on sending a break byte (always 0x55), sync byte, frame id, data load and checksum to validate the message. Most of these are handled through the library, and you only need to configure the desired bits to listen for changes made and the frame id which identifies the component.

![https://ni.scene7.com/is/image/ni/LIN_frame_20090802104146?scl=1](https://ni.scene7.com/is/image/ni/LIN_frame_20090802104146?scl=1)
