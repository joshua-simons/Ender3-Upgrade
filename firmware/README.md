# Installing a Bootloader and Flashing Firmware:

**Note: I used a bunch of sources to accomplish this, but I found [this video](https://youtu.be/fIl5X2ffdyo) to be very straight-forward and helpful.**

## Bootloader:

I ended up deciding on using the TH3D firmware.  It is a Marlin Variant, but is simplified, and customized for the TH3D products.  I figure that as a beginner, streamlined configuration is probably a better way for me to go.  I also am going to use the TH3D EZABL sensor, and setting it up with firmware that is made for it seems like a way to avoid headaches.  Once the bootloader is flashed, it is trivial to upgrade or change the firmware via USB, so I figure if I want to change over to Marlin once I get a better grasp on what I'm doing, or I require something that Marlin offers that TH3D doesn't, then changing the firmware will be pretty simple.

### Steps:

1. Install Ardrino IDE from TH3D. Make sure it is the one from TH3D as it comes with all of the libraries you will need pre-installed.
2. Open up main board cover on the Ender 3
3. Configure the Ardrino IDE to configure the UNO as a sanguino 1248P board and programmer
4. Wire jumpers from Ardrino Uno to the Ender 3 main board
5. Burn Bootloader

