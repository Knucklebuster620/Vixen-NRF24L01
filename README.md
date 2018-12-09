# Vixen-NRF24L01
I decided I wanted to create an arduino code that used the NRF24L01 to transmit the data to multiple boxes allowing me to build smaller more portable outlet control boxes and not have a dozen data wires running across my yard.  Building my boxes this way allowed for multiple costs savings such as, (less long heavy gauge extension cords are needed because I can now run 1 cord directly to the lights I want to control then if needed, most the time not, run small cheap cords to run 8 lights, where as other people have to run 1 large cord to their box and then run long cords to each light,  another way this saves on cost is with it being wireless I do not require multiple long runs of usb extension cords, or powered usb hubs. I simply build 1 transmitter and it stays close to my computer or raspberry pi). 

The first ZIP file contains the code to control up to 254 outlets (32 boxes, 31 with 8 outlets, 1 with 6 outlets), but will require modification to the Arduino IDE.

The second ZIP file contains the code to control up to 56 outlets (7 Boxes 8 outlets each) without the need to modify the Arduino IDE.

The third ZIP file contains the files to modify the Arduino IDE for the 254 outlet code.  (only tested on Arduino IDE 1.8.6)
