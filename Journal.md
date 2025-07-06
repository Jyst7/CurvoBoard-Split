**CurvoBoard Split, 12h**

**Jul 3: Brainstorming and reasesearch**

I needed to fully figure out how I was going to design the board, after seeing how other ergonomic boards do it I decided I would split each half into their row and the thumb cluster, this means each side would have a seperate pcb for every row and the thumb cluster so 5 rows +1 thumb cluster per side. to connect them I will add a hole on each side of the rows and I can 3d print a bracket to connect them all on the angle I want. I also am hoping by the end i can used the space created by having the angle to put the battery and microcontroller.

![image](https://github.com/user-attachments/assets/73e336d7-f307-4464-8104-90cc4e6ca320)
![image](https://github.com/user-attachments/assets/44ff475f-5e49-496b-8b5e-7026a2124198)

**Jul 4, 4h: Schematic + PCB**

I created the schematic today, there were a few iterations to do and I decided to go as simple as possible, I first made a matrix just to make sure I know how it should be wired, then I made a singular row with each column getting a through hole that I can wire to the other ones as well as a through hole for the row itself to be wired the same is done for the thumb cluster. these will be hand wired with solid core 22awg wire to the microcontroller. The microcontroller is a nice!nano as they are really easy to use with zmk for split keyboards I will also be using a lipo charger and a lipo as the nice!nano works wirelessly.

<img width="876" alt="Screenshot 2025-07-05 at 5 03 57 PM" src="https://github.com/user-attachments/assets/75d0db20-c70f-420e-942e-0b2efc3ea6bf" />
<img width="1081" alt="Screenshot 2025-07-05 at 5 04 14 PM" src="https://github.com/user-attachments/assets/9d3c89a2-930f-44ff-9c2f-7fd5a11c8f68" />

**Jul 5, 3h: Starting Cad**

I started the design of the 3d model by first figuring out the angle for each row, I am putting the rows behind the fingers on a shallow angle and the rows above on a lightly sharper angle this should be comfortable from the mock up I printed but it can always be changed later. I then added the section that makes the board sit flat and made sure the screw holes can still be accessed. Now the last part is adding the thumb cluster and this is difficult because it can’t directly attach to the board it needs to attach to two different mounting holes to be sturdy while the mounting holes are on two different angle. My first idea with thtat is to start with the first mounting hole and add the other one later the only other issue I am having is just making sure that It doesnt get in the way of any of the parts under the pcb so I think I am going try a couple things and I’ll see what works.

**Jul 6, 3h: Finishing Cad, firmware and bom**

I finished the desing of the keyboard, to solve yesterday's issue I realized extruding up to face copies the angle of the selected face making me able to easily connect the parts from then. for the thumb cluster to make it look good I added a small plate that goes on top of it. I did not cad in the screws but any m4 screw around 1/2" should work well. and I chose NuPhy Cowberry switches. I followed zmk's steps to create the firmware and make the keyboard layout, it is named corne in the files but I made it my own layout.

https://www.aliexpress.com/item/1005007036819050.html?

<img width="1113" alt="Screenshot 2025-07-06 at 3 40 24 PM" src="https://github.com/user-attachments/assets/dbb339f2-b559-4828-9f66-3fd760efd1ac" />
