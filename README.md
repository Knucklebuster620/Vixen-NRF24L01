# Vixen-NRF24L01
I decided I wanted to create an arduino code that used the NRF24L01 to transmit the data to multiple boxes allowing me to build smaller more portable outlet control boxes and not have a dozen data wires running across my yard.  Building my boxes this way allowed for multiple costs savings such as, less long heavy gauge extension cords are needed because I can now run 1 cord directly to the lights I want to control then if needed, most the time not, run small cheap cords to run 8 lights. Where as other people have to run 1 large cord to their box and then run long cords to each light. Another way this saves on cost is with it being wireless I do not require multiple long runs of usb extension cords, or powered usb hubs. I simply build 1 transmitter and it stays close to my computer or raspberry pi and the receivers just require power that they are going to get anyhow to control the lights.  I don't know if I can call this a cost savings as well but it uses Arduino UNO, NANO, and PRO MINI boards instead of the expensive MEGA boards most people use and you ultimately can control more outputs than the MEGA can directly wired. I wanted this system for ease of use so that if my wife or kids wants to help me set up lights I just tell them something like "take box #5 to the left side of the house and connect the lights in this order" I don't have to explain usb cables or anything else.  Another way it makes it easeier is  most people will not need more than 56 or 254 outlets to control so this means you only have to keep up with 1 COM port on your computer.  Something else that is nice about this setup compared to others is the fact that you do not have to build it all at once, you can build any number of boxes you want to start and just keep building more through the years without having to modify any of the older boxes you built.  For example say you built 7 boxes (254 outlet setup) the first year, next year you plan to build 5 more, you will not need to modify the original 7 boxes or transmitter in any way you just pick up with what outputs you left off at.  You can do this all the way until you reach the 254 outlet limit.  Yes this theory applies to the 56 outlet setup but once you build the 7th box you have to start all over with another transmitter and new boxes.  With that being said that is why I recommend the 254 outlet setup, plenty of room for growth and the modifications to the Arduino IDE are easy. I have already done the leg work and provided the files for the modification, and the good news is the modification just adds more Arduino boards that have the modification attached to them so when you go to upload you get to pick which board you want, for example Arduino UNO or Arduino UNO (256 Serial Buffer), so it will not affect other projects that you want the original IDE code on. Also it is not permanent so if you do not like the modifications to the IDE you can easily remove them.

I do have one thing that some people may consider a disadvantage (I don't see it as such I think it is an advantage in durability). To build my boxes the way I do will require a lot of desoldering and soldering of components. This can make building these boxes a bit time consuming, but just as much time to build any other style box people have built.  That being said to build my boxes exactly as I do will require a higher level of soldering skills so please be warned. 

I run these boxes on my own house and am fully confident in their quality, but with how things go in todays world I have to make the following statement.  Please do not think I am trying to be rude, I am just trying to protect myself.

***Please build at your own risk! I am not liable for any damages to any items or equipment caused by building/operating the items described. I am also not liable for any injuries that you or others may incur during the manufactor or operation of the items descirbed. You are responsible to make sure you do not exceed the current carrying capabilities of any wire or outlet, etc...  When following these instructions you accept soul responsibility for any injuries or damages incurred to yourself or others.***

The first ZIP file contains the code to control up to 254 outlets (32 boxes, 31 with 8 outlets, 1 with 6 outlets), but will require modification to the Arduino IDE.

The second ZIP file contains the code to control up to 56 outlets (7 Boxes 8 outlets each) without the need to modify the Arduino IDE.

The third ZIP file contains the files to modify the Arduino IDE for the 254 outlet code.  (only tested on Arduino IDE 1.8.6)

The fourth ZIP file contains the parts list for the FM transmitter I used for my light show.

The fifth ZIP file contains the parts list for the Vixen-NRF24L01 Transmitters and Receivers.

I will eventually make a YouTube video showing how I assembled everything.
