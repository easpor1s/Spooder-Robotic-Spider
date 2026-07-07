# Spooder — Journal Export

- Exported at: 2026-07-07T22:23:32Z
- Project ID: 4099
- Entries: 36

## Entry 1
- ID: 10595
- Author: allenlin0728
- Created At: 2026-05-31T05:44:50Z

### Content

I started by looking at an old prototype of one of the arms that i made a while back and kind of just taking in the design, but ended up deleting most of it. I started to research about herringbone gears, as we were going to 3d print some of them for our design, and pulleys/belt, which I was not very experienced with. From this I did a little bit of scouting of parts and created a very rough draft on FUSION of our arm, with the pulleys, herringbone gears and the servo motors. The belts/pulleys were the main focus, where I decided for a 300mm long GT2 9mm pulley/belt from my research.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQxMzMsInB1ciI6ImJsb2JfaWQifX0=--08f22ff7582095afcd0169cc661e6c7ee83e8ca1/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQxMzYsInB1ciI6ImJsb2JfaWQifX0=--b20be30344e053fbb28d6fb724dc22941db71d95/image.png)


### Recording Links

- https://www.youtube.com/watch?v=wEREaV_vIaY

## Entry 2
- ID: 10819
- Author: allenlin0728
- Created At: 2026-06-01T03:55:55Z

### Content

I started to polish my old design up, where i spent lots of time joining and creating different parts, like the pulleys/helical gears. But after discussing, Gavin and I decided to scrap the old design entirely after seeing some other designs of a similar robot, where we now decided to use 3 servos, and 6 legs to make the movement more refined smooth. This meant we had to scrap our old design, and create a new one. After learning the size of our servos, which was much lighter/smaller than expected, we decided on directly placing the servos onto the joints, with ball bearings for less friction. This now allows us to turn our legs individually, but requires much more servos.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQ2ODYsInB1ciI6ImJsb2JfaWQifX0=--710577fcc6c2ff736f58be18ba8fce0e2de90e73/image.png)


### Recording Links

- https://www.youtube.com/watch?v=X4d5mncq7Mc
- https://www.youtube.com/watch?v=3uG8w2orfYI
- https://www.youtube.com/watch?v=HCluzsvRUsA

## Entry 3
- ID: 10820
- Author: deez.ducks.ca
- Created At: 2026-06-01T03:57:54Z

### Content

I researched and sorted all the electronic components and materials needed for the robot and added them to a spread sheet with individual and total costs. I created our Github and wrote the projects read me as well as uploading the cost and materials spread sheet onto it. I started the logo for the project zine and added it to the Github. Some other additional house keeping items have also been taken care of. I have also determined the basic work flow we are going to use to electronics such as which modules attach where, how is power stepped down and delivered etc. (started at 1:40 ended at 9:30, OBS wasnt working for a few hours and didnt realize)

![cost.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQ2ODMsInB1ciI6ImJsb2JfaWQifX0=--0a0149196a45b8ba4a71c36c3a60af4002b1cf34/cost.png)
![git.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQ2ODQsInB1ciI6ImJsb2JfaWQifX0=--85da68fa227eac97c4869a47715eb035304441d1/git.png)
![image.jpg](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQ2OTYsInB1ciI6ImJsb2JfaWQifX0=--824e1f2843b4f1b58e45c75d2b1a9fb1e2d518ed/image.jpg)
![ddd.jpg](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQ2OTcsInB1ciI6ImJsb2JfaWQifX0=--3251d864eb0de617e8cc84bc88b7cb333672b9cd/ddd.jpg)


### Recording Links

- https://www.youtube.com/watch?v=XxXYVmYsMW0
- https://www.youtube.com/watch?v=baPjPJVgMh8
- https://lookout.hackclub.com/api/media/7c6b96f3-029c-4d9d-af1d-7212b8e67b17/video.mp4

## Entry 4
- ID: 11060
- Author: deez.ducks.ca
- Created At: 2026-06-02T04:23:40Z

### Content

Polished GitHub, added milestone target and fixed some formatting issues. Researched and compiled electronics -> soldering iron, servos. Solved the major problem of how to power the Raspberry Pi 5 mobile on the robot at a reasonable cost. -> 67W Ugreen power bank with a USB-PD 2.0/3.0 to 5V 5A converter board. Researched and planned additional mounting hardware components to be used. Made a basic circuit diagram on how the electronics will be wired together. 
![circuit.PNG](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjUzMzksInB1ciI6ImJsb2JfaWQifX0=--cfd0319996203554d26a93c59499833dce4f5b09/circuit.PNG)


### Recording Links

- https://lookout.hackclub.com/api/media/a696c47c-5837-4988-a421-9487be0b5eb6/video.mp4

## Entry 5
- ID: 11065
- Author: allenlin0728
- Created At: 2026-06-02T04:42:57Z

### Content

I touched up the leg assembly by adding a pair of knobs as a axle fit for the ball bearings. 
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjUzMzcsInB1ciI6ImJsb2JfaWQifX0=--3213c5f9f22807a25216efc5767b18de13e39de4/image.png)

After this I started on the main design, which would used 6 of these leg assemblies, but after moving some of the legs to the alternate side and flipping them around and rotating, I realized I had to mirror the other leg for a right side and a left side to have the motors oriented correctly. So I copied and edited one the leg assembly, flipping the top motor, which when rotated in the main assembly would allow for an alternate or mirrored leg. 

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjUzNDAsInB1ciI6ImJsb2JfaWQifX0=--670c2b131e426ce3942848e980d59f914dd960a7/image.png)
left side

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjUzNDEsInB1ciI6ImJsb2JfaWQifX0=--5c9ec4fd06ae0bd706da55821020eab17c811d97/image.png)
right side

From this I positioned the legs temporarily at a even increment for simplicity.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjUzNDgsInB1ciI6ImJsb2JfaWQifX0=--24fee1398db1675271158758057619519aa259fe/image.png)

One thing I noticed though is that the curve of the claw of the spider also needed to be mirrored, and possibly the central joint motors

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjUzNDksInB1ciI6ImJsb2JfaWQifX0=--81725b713b50b7c7570b3233f740a3e5addf1a73/image.png)


I decided to do this tomorrow as it was getting that but this is to keep note of it.

### Recording Links

- https://www.youtube.com/watch?v=mTfh1b1T4Z4

## Entry 6
- ID: 11283
- Author: deez.ducks.ca
- Created At: 2026-06-03T02:57:15Z

### Content

Today I made a polished wiring diagram that was an enourmous improvement upon the previous one. This layout includes all the hardware that will be required for the robot to operate. This wiring diagram would allow us to assemble the robot more quickly and more efficiently, as it serves as an instruction sheet for the assembly of the electronics. Additionally, I determined that a Pimoroni Yukon would be a more suitable dev for our robot as it natively supports a direct connection to 2S LIPo and its hot-swappable servo modules. 
![spooder wiring.PNG](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjU5OTcsInB1ciI6ImJsb2JfaWQifX0=--c99b27f63a0efdec156740169ec66fc2e5bc9dc3/spooder wiring.PNG)


### Recording Links

- https://www.youtube.com/watch?v=EKXB0rfb_ZY

## Entry 7
- ID: 11302
- Author: allenlin0728
- Created At: 2026-06-03T04:34:55Z

### Content

I decided to start by fixing some of the errors that came up when I was trying to combine some of the bodies for the joints of the legs. This required me to move a lot of sketches around and reestablish new profile planes. I also split the end of the legs where it comes to a singular point in half, where I could now 3d print the main part of the piece with a regular plastic and create TPU tips that I could glue on for traction. But because I only edited one of the legs to fix the errors and modify it, I decided to scrap the old left leg, and to just copy the right leg and to flip the components I needed, which was the direction of the point on the end of the leg and the body motor direction. I also downloaded files for bearings and then added them in to both sides.


 
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjYwMzYsInB1ciI6ImJsb2JfaWQifX0=--33ab170b3fe930e3a902d76cd51b15ebf6f3c5c3/image.png)
right side

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjYwMzcsInB1ciI6ImJsb2JfaWQifX0=--6442936c7a91af7081dbd5fb84cc29785ed9fb2a/image.png)
left side

### Recording Links

- https://www.youtube.com/watch?v=9oQujQrA6ts

## Entry 8
- ID: 11546
- Author: deez.ducks.ca
- Created At: 2026-06-04T05:10:30Z

### Content

I completely overhauled the bill of materials and was able to reduce the cost from $777 to $553, and I expect to be able to further reduce it later on. Most of the electronics, how they work, and how they integrate together are completely new to me, so I am learning as I go. I determined that a Pimoroni Yukon with 5 servo modules would serve our purpose the best, as it has a built-in LiPo battery connector. This board also allows us to scrap the Raspberry Pi and a separate servo board altogether, which makes assembly much simpler and also removes the need for a step-down converter for a servo board. This saves a ton of time and money. Additionally, I found that DS 3225 servos are much better suited for the project than the DS 3218 servos we were originally planning to use, as it provides a faster rotation speed and increased torque at the same price as the DS 3218 servos. 
![spooooder.PNG](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjY4NDUsInB1ciI6ImJsb2JfaWQifX0=--aac737539eed8612c9e7048de4e37845fe682104/spooooder.PNG)


### Recording Links

- https://www.youtube.com/watch?v=buhjz0CnnKA

## Entry 9
- ID: 11548
- Author: allenlin0728
- Created At: 2026-06-04T05:39:51Z

### Content

I downloaded the cad files for the brass heat set inserts that were used. For the m2.5 screws, I chose countersunk flat head screws because I wanted the minimal profile as this was necessary for the attaching the servos to the components while making the assembly as thin as possible. For the m4 screws, because these were primarily for mounting the body of the servos, I used regular button head screws for a smaller profile and no need for countersinking. One problem I encountered while trying to add these screws and inserts was that the mounting screws for the servo arm were very close together, meaning I couldn't use two screws regularly to mount it.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjY4NDcsInB1ciI6ImJsb2JfaWQifX0=--3820992e230e3f7e538b3222306251ae62d061f7/image.png)


I resolved this by putting a button head screw on the other side so the screw heads would not interfere with each other.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjY4NTIsInB1ciI6ImJsb2JfaWQifX0=--96a793db73703b1e39b0cef4606c337f711195c1/image.png)


This is the assembly with all the screws, bearings and inserts:

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjY4NTMsInB1ciI6ImJsb2JfaWQifX0=--2bf07e3e4a31609af82162f498a2c8c851965480/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjY4NTQsInB1ciI6ImJsb2JfaWQifX0=--4997a3873bbef6bd5e1eb8c0fa7cc6b348f9c013/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/c91c6fc0-5f60-4c47-87cc-74efcbfb8cee/video.mp4
- https://lookout.hackclub.com/api/media/f14bfdbd-4bc3-429a-b641-7cb3baa93ea6/video.mp4

## Entry 10
- ID: 11777
- Author: deez.ducks.ca
- Created At: 2026-06-05T05:18:36Z

### Content

The circuit diagram has been redone as we found a Raspberry Pi 4 in storage. This enables us to run more complex code and add new features. A major pain point previously was that the Pimoroni Yukon did not have any USB Type-A ports, which meant connecting a 2.4GHZ game pad would have been extremely difficult, but with the Pi, it has the required ports. Additionally, this allows us to use an 8BITDO  controller, which is known to work with the Pi but has absolutely no documentation with the Yukon. 
![circuitv2.PNG](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjc0NTgsInB1ciI6ImJsb2JfaWQifX0=--a837dbfa00e7258152d0b83b322fd16257a7f4b5/circuitv2.PNG)


### Recording Links

- https://lookout.hackclub.com/api/media/511be3ef-2075-4422-8def-bac8b7580443/video.mp4

## Entry 11
- ID: 11778
- Author: allenlin0728
- Created At: 2026-06-05T05:36:59Z

### Content

I finalized the legs, doing the last adjustments such as creating the right leg with the new components. With this I set up the legs in their correct orientation, and started to find the cad files for the other electronics as a guideline to start creating the body. 

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjc0NTksInB1ciI6ImJsb2JfaWQifX0=--4328af2566cece3fceec42503db9af85512f6c97/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/ef52723f-4624-44a8-849a-aead316a4be1/video.mp4

## Entry 12
- ID: 11988
- Author: allenlin0728
- Created At: 2026-06-06T04:10:28Z

### Content

Today I started to create the main body of the spider. I started by taking and finding the cad files of the electronics such as the Raspberry Pi 4, the IMU, the Pimoroni Yukon, and the batteries and creating a structure/layout for them. I decided the layout to involve having the power bank and the battery to be at the bottom for hotswapping, and the main electronics on the upper section of the body. I also ensured that the IMU was positioned in the exact center of the body for precision. 
![Screenshot 2026-06-05 180103.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjgwNzEsInB1ciI6ImJsb2JfaWQifX0=--9e0d176cc892e21dc50334d6f19c84eb80137c99/Screenshot 2026-06-05 180103.png)
![Screenshot 2026-06-05 180126.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjgwNzYsInB1ciI6ImJsb2JfaWQifX0=--30727fe089aad9648e9354e9025972bcf74c72f1/Screenshot 2026-06-05 180126.png)

With this I started to experiment with the positioning of the legs, at first I decided to put the legs relatively far away from the center, but that made 3d printing the body difficult, and unnecessary weight. From this I moved them so they would intersect the rectangular body, creating a hexagon star like shape, with just enough space for the body and legs. 
![ss.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjgwODAsInB1ciI6ImJsb2JfaWQifX0=--1fb3eaa19e014f9089276670fc40b88d01f4a50a/ss.png)
I now added the base plate, and positioned the Raspberry Pi and Yukon side by side, elevated up with standoffs, allowing the IMU to be positioned in the middle right under.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjgwODEsInB1ciI6ImJsb2JfaWQifX0=--387747ade69d2bc9834dc4b5b611c686714adb43/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/f43f4d79-c17d-47ea-8be7-41a8878a5e98/video.mp4
- https://lookout.hackclub.com/api/media/da010aa7-f9f8-481b-81c4-ef146afcb895/video.mp4

## Entry 13
- ID: 11993
- Author: deez.ducks.ca
- Created At: 2026-06-06T04:41:19Z

### Content

I researched libraries and dependencies required for controlling the robot as we have never attempted a servo controlled walker bot before. I determined that PIGPIO is the best software for us as it avoids servo jitter which would be a catastrophic error for our robot. We did some brainstorming together and determined the next steps and course of action for implementing code and the positioning of Spooder's legs. On the hardware end, I managed to get the Raspberry Pi 4 working as it previously had a corrupt image and updated the Bluetooth and Python packages. Troubleshooting the Pi was the biggest challenge today as I have had no experience with single board computers before hand so I was learning as I went. I found the Raspberry Pi OS Lite was the optimal operating system for us as it saves the limited RAM we have on the pi and allows us to run heavier software. I also attempted to connect an older Xbox one gamepad that we had in storage but to no result as the controller already had a pairing issue. 
![IMG_3159.jpg](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjgwOTIsInB1ciI6ImJsb2JfaWQifX0=--01631134f84a030a8bfb19dc48d9db2a99246af2/IMG_3159.jpg)


### Recording Links

- https://lookout.hackclub.com/api/media/ff5005c6-b4b4-4ba0-ab0b-f69e94fd0625/video.mp4

## Entry 14
- ID: 12212
- Author: allenlin0728
- Created At: 2026-06-07T05:58:29Z

### Content

Today I started to add the top section of the main body, where the top bearings are housed. But I noticed that a lot of the sketch lengths were different for some reason, so I assumed something about the main shape of the body was irregular, so I decided to redo it.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjg2NjMsInB1ciI6ImJsb2JfaWQifX0=--d39065e120ea78a641fb0ea01fe709ac43057e39/image.png)


This new design was a little simpler than the previous, and was sligthly smaller, which meant that I had less room for error and slightly lower weight. From this, I started the top section of the housing, which would be composed of pillars coming from the bottom section.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjg2NzIsInB1ciI6ImJsb2JfaWQifX0=--3be5e48ca3e2ae998ec8397b78bd66e932d69780/image.png)

I added a top cover with the loft function for structure


### Recording Links

- https://lookout.hackclub.com/api/media/b4c09e7a-00df-4e57-a936-9556db4edfdf/video.mp4
- https://lookout.hackclub.com/api/media/550bc495-696c-4d6f-b2fa-a5c7497e75ea/video.mp4

## Entry 15
- ID: 12425
- Author: deez.ducks.ca
- Created At: 2026-06-08T04:09:31Z

### Content

An issue I ran into today was getting file transfer using VScode SSH to function which is how we plan to transfer files from a computer to the Raspi. This issue is still unresolved. I started to code the control software for our robot  but only got very basic main control, calibration, and readme finished as we do not have the required hardware. I started on our Zine page and sketched out the spider character that is Spooder. 
![Untitled 6.PNG](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkxMjcsInB1ciI6ImJsb2JfaWQifX0=--0c1167f60fb3701ef2defabc647214f5f3b6ec6e/Untitled 6.PNG)


### Recording Links

- https://www.youtube.com/watch?v=PIIL-6kyG3A
- https://www.youtube.com/watch?v=Ju4qd_anXFk
- https://lookout.hackclub.com/api/media/97aa1a68-50c6-4adb-942d-2ef4f511fbfe/video.mp4

## Entry 16
- ID: 12429
- Author: allenlin0728
- Created At: 2026-06-08T04:57:04Z

### Content

I started by finishing up the bulk of my design, finalizing the enclosure and fixing some of the little details on it. I also added the mount for the power sources, which were the power bank and the battery, which would rest on the bottom of the robot. 

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkxNDksInB1ciI6ImJsb2JfaWQifX0=--02a458740db4cb53d76c8191ff1acf5dbe0a0a56/image.png)
I also experimented with a screen I found on adafruit, which could be mounted and used to display different things in the future, and I cadded a mount for it.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkxNTIsInB1ciI6ImJsb2JfaWQifX0=--33838d2915016e73703966a7ba72c658625da90d/image.png)
However, when I started to export the files and prepare them for 3d printing, I realized that my 3d printer was too small for the main body. 
![spooder v17.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkxNDUsInB1ciI6ImJsb2JfaWQifX0=--9a7e1ccfc38a0de0bd5f5c44434e83a968ba8444/spooder v17.png)
![Screenshot 2026-06-07 161750.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkxNDYsInB1ciI6ImJsb2JfaWQifX0=--3ec0ebeb7d604659cd9d27b61d5bfa5c94cbd4c5/Screenshot 2026-06-07 161750.png)
This meant that I had to redo the shape of the main body, moving the legs closer apart so the body would be less long. A lot of the sketches were messed up, which meant that I had to also re-extrude a lot of the shapes. Although this was a great set back, it also allowed me to fix one of the problems, which was the accessibility of the body, where a large body as one piece would mean that building would be very difficult/impossible in some places. I solved this by using a top enclosure and a bottom enclosure, mounted together with screws instead of one solid body, which would allow me to access the inside of the robot with ease, and be able to close it afterwards with a casing.  The cad is still unfinished, as i still have to figure out a lot of the wiring and accessibility, and the mount for the display.



### Recording Links

- https://lookout.hackclub.com/api/media/d9fe82c6-1c84-4215-8441-8b2910a375dc/video.mp4

## Entry 17
- ID: 12690
- Author: deez.ducks.ca
- Created At: 2026-06-09T05:34:50Z

### Content

Today I started on the first iteration of our zine page. I used a typeface that matches the character that we believe our robot represents, and chose a colour palette for the Zine page and any future designs related to our bot. For tomorrow, I want to find a way to implement a wireframe diagram of our robot on the zine page, as I really enjoy the aesthetic it adds. 
![Capture.PNG](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjk3ODQsInB1ciI6ImJsb2JfaWQifX0=--9b1b00d456b2786c6b8e1b983888b13087861e44/Capture.PNG)


### Recording Links

- https://lookout.hackclub.com/api/media/19ec2be8-a3d6-4b82-a01d-a47af3ede811/video.mp4

## Entry 18
- ID: 12697
- Author: allenlin0728
- Created At: 2026-06-09T06:28:06Z

### Content

Today's work was to refine the core design of the spider that I currently had. I started by trying to track the size of the main body, which was now two pieces, but because of the new mounts for the servos that stuck out of the body, it was still too large for my 3d printer. This meant I needed another method to actually manufacture this with a reasonably sized printer. I opted for splitting the body into more pieces, where now it was now mostly 3 layers: the bottom mount, where all the controllers and the battery pack was mounted, the middle section which was comprised of a left and right section, which held the mounts for the servos and the bearings, and the top casing, which would have the display and also the top enclosure. All of these parts would be mounted together with screws, and is now fully 3d printable on my K1C, or a print bed of 220x220x235. From this I also bent the legs in a more natural way, where before only the last joint would be bent for convenience, but would not be accurate and would look a little weird, and now I would raise the first joint up and the second joint down, making a more natural leg joint that would be replicated in the project IRL. This came with lots of difficulty. At first I tried to edit all my leg files to have them bent correctly, however, this didn't do anything to my actual assembly's legs. Importing the new legs one by one and replacing them would also not work, as I had a sketch that relied on the old legs, and replacing them would mess all of that up. This meant that I had to manually edit all the joints, which would be very time consuming and would mean I had to select a ton of components, but in the end, I got it to work, making it visually accurate for the zine and github.


One of my timelapses from yesterday was seemingly deleted after I accidentally refreshed the lookout page but now it appeared again so i will be submitting that as well.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjk4MDEsInB1ciI6ImJsb2JfaWQifX0=--6d35d1bb0c42860b07113b1df371ac5fcdd24e55/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/d386b9d8-1e53-4be7-89a4-fa2b9229bcb9/video.mp4
- https://lookout.hackclub.com/api/media/46fa690c-a89c-46a9-80ad-902d3cf75ac6/video.mp4
- https://lookout.hackclub.com/api/media/51d6e1c4-6383-41f8-bef2-23e75b9a81f8/video.mp4

## Entry 19
- ID: 12945
- Author: deez.ducks.ca
- Created At: 2026-06-10T05:51:10Z

### Content

I revised the BOM and fixed some broken links. I finalized the Zine for the project and will only need to make some subheading text more legible tomorrow. 
![zine png.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzA0MjMsInB1ciI6ImJsb2JfaWQifX0=--6509b742a42e9ae6c3f899cdf43c910155ae0f3a/zine png.png)


### Recording Links

- https://lookout.hackclub.com/api/media/d43bfa0b-9c79-496c-bc32-51420e5aaa2e/video.mp4

## Entry 20
- ID: 12946
- Author: allenlin0728
- Created At: 2026-06-10T05:54:25Z

### Content

Today I added side guards for the body, which would prevent parts from falling out, although not very much contribution structurally. To save filament, I holed it out with a Voronoi diagram pattern that I used  for a lot of other areas, which would add style while being functional and relatively strong. 
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzA0MjYsInB1ciI6ImJsb2JfaWQifX0=--f678306a8d89cc8da70c901a7f239985e2e02d07/image.png)

I also created the screen mount, which would be an external part/assembly of components, for organization, and mounted it to the main body, using the loft function to attach it to the top enclosure. I also had to create a hole in one of the side plates for the display cable to go through.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzA0MjUsInB1ciI6ImJsb2JfaWQifX0=--665cf4f45a79f48fefc34951f4f76822a19c374d/image.png)

Now the design is done to my knowledge, but is still missing some parts like screws and inserts for a full assembly. 
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzA0MjQsInB1ciI6ImJsb2JfaWQifX0=--5a0ef33b37b28eb2b586d26da944d1a369b6dc3f/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/7319f4cf-a0c6-4533-8021-827456508346/video.mp4

## Entry 21
- ID: 13127
- Author: deez.ducks.ca
- Created At: 2026-06-11T02:21:11Z

### Content

Today I finished the zine and added it to GitHub. I added all the parts required to build the robot to the BOM, including parts that we already own and updated the GitHub with it. I updated the GitHub README to get up to speed with the latest iteration of Spooders' design as well. 
![ddd.PNG](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzA5OTIsInB1ciI6ImJsb2JfaWQifX0=--dcaf6ca4ed121606d465efbd3731760ff67ac963/ddd.PNG)


### Recording Links

- https://lookout.hackclub.com/api/media/c188af03-4207-4d36-ae28-f73ba242787d/video.mp4

## Entry 22
- ID: 13171
- Author: allenlin0728
- Created At: 2026-06-11T05:59:12Z

### Content

Today I started to assemble the whole design, adding the proper screws, inserts and bearings to the correct places. I then created a spreadsheet with the data for a small pieces, which I would then use to update the BOM. 

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzEwNzcsInB1ciI6ImJsb2JfaWQifX0=--9b74f1427263d1e7f03a86466285d42670a2fed8/image.png)


I also figured out the original display I used, which was an adafruit 5inch tft display which required a seperate board that costed over 50 dollar CAD could be replaced with an led matrix, which has more suitable dimensions, and could be connected without a seperated board, and had a lower cost in general. 


![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzEwNzgsInB1ciI6ImJsb2JfaWQifX0=--b8d9132bbba48e7a903958268aa2869b4141aede/image.png)



edit: my computer crashed midway but when i thought it was fine the time lapse turned completely dark for some reason?




### Recording Links

- https://lookout.hackclub.com/api/media/d54fbae7-8229-49e7-b803-13778409952f/video.mp4

## Entry 23
- ID: 13374
- Author: deez.ducks.ca
- Created At: 2026-06-12T04:01:59Z

### Content

Today I finalized as well as organized the repository and revised the Zine to reflect some new material choices. We started printing a few small test components to make sure they will fit together properly. Today I also resolved the issue where we could not sent files to the raspberry pi due to a public key error and successfully connected our controller to the pi and made sure it will always work immediately.  
![spooder_2026-Jun-12_03-49-51AM-000_CustomizedView15966012020.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzE2NjUsInB1ciI6ImJsb2JfaWQifX0=--145299678a465079f024d4a399d24563bb250ede/spooder_2026-Jun-12_03-49-51AM-000_CustomizedView15966012020.png)


### Recording Links

- https://lookout.hackclub.com/api/media/c46fa32e-8cfc-46e6-ad01-4b6a717d9616/video.mp4

## Entry 24
- ID: 13382
- Author: allenlin0728
- Created At: 2026-06-12T05:11:29Z

### Content

Today I started the mount for the led matrix, which was 32x64 with a 2.5mm pitch. However I couldn't find any official cad files or datasheets for it with the mounting holes, but luckily I found an old post with all the measurements for the mounting points.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzE2ODgsInB1ciI6ImJsb2JfaWQifX0=--64463bd26c37970aa54792e5bee930e02ef61fea/image.png)


I then used this to edit my old "screen" mount cad to fit the new LED matrix, and then added it to my assembly with my other components for the screen. I had some difficulty connecting it to the top enclosure, but i managed to make it work with the loft function and splitting the back of the matrix mount with a sketch. 

This is the fully assembled cad for now

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzE2OTAsInB1ciI6ImJsb2JfaWQifX0=--ef6c2df32f7a11dd530c9beaae7c65178dab9f4c/image.png)
I did run into a problem though, which was with wiring of the matrix and the IMU. Because the matrix used most of the GPIO ports including the I2C pins, it could not be used with the IMU, which needed those ports. This could be solved with a led matrix bonnet, which would be attached directly on top of the pi and connecting to the matrix, but still leaving the I2C pins open. Once I figured this out, I fully updated the BOM, which would now include everything needed, and was now formatted in a better way for a CSV file. Before the BOM had hyperlinks, but after exporting to csv i realized it didn't actually export the links and exported the titles of the links, so I changed them all to regular links and pushed it to the github.

I also started to export the F3Z file to the github, which was the complete cad of the assembly, however the file size was too large for the web version of github, which made me use the desktop version for the first time in a while.

I also exported all the 3d models for 3d printing, and added them into a folder for the github. In addition, I also laid out all the files and models on my slicing software, and thankfully, all of the models fit nicely.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzE2OTEsInB1ciI6ImJsb2JfaWQifX0=--9a34d2bce005d79667037160bc98bed5293b933f/image.png)


From this I decided to start 3d printing the first test run of the leg, which would allow me to see if the assembly would work or not, in a cheap PLA filament I had beforehand.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzE2OTIsInB1ciI6ImJsb2JfaWQifX0=--66deaf8c21b3d3f8a05335de25df57dc11add7a5/image.png)
Now most of the design is done, leaving only an update to the zine, which used my old cad render, and the wiring diagram, which needed to be finished.



### Recording Links

- https://lookout.hackclub.com/api/media/6072bd65-821b-409f-b922-38a30c82cbac/video.mp4
- https://lookout.hackclub.com/api/media/63f370cc-74c3-43dd-b58c-266aacffe299/video.mp4
- https://lookout.hackclub.com/api/media/7554433f-f54f-429d-bfc5-9048ff405e09/video.mp4

## Entry 25
- ID: 13533
- Author: deez.ducks.ca
- Created At: 2026-06-12T19:18:15Z

### Content

Properly formatted BOM and added description and owned materials. Created new and updated wiring diagram so assembly will be smoother, 
![Spooder Circuit.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzIxMDIsInB1ciI6ImJsb2JfaWQifX0=--e92079df16698625cdf1069a849293672491c3da/Spooder Circuit.png)


### Recording Links

- https://lookout.hackclub.com/api/media/af99b3c3-6794-4603-a782-1103430dc81a/video.mp4

## Entry 26
- ID: 13645
- Author: allenlin0728
- Created At: 2026-06-13T05:24:53Z

### Content

After 3d printing the components for the legs I removed the supports and assembled it, although not with a loose fit because of the lack of bearings. However, I realized one of the joints of the legs were being blocked by the mid section of the leg. So I shrunk the  size of the support in the middle for it, and now it should not hit the joint. I also started to 3d print the guards with CF petg, as it was the only other filament I had. I also revised the entire project for submission, and submitted it. 
![IMG_5071.jpeg](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzIzMjUsInB1ciI6ImJsb2JfaWQifX0=--13379d235ea23f05b136ba4856f1216088e16d01/IMG_5071.jpeg)
![IMG_5068.jpeg](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzIzMjYsInB1ciI6ImJsb2JfaWQifX0=--9bccb727e886cadf97dab4867202a628d44eeaad/IMG_5068.jpeg)

![IMG_5072.jpeg](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzIzMjcsInB1ciI6ImJsb2JfaWQifX0=--1a9880c4913b5b54035666e0482051d32a3912cb/IMG_5072.jpeg)


### Recording Links

- https://lookout.hackclub.com/api/media/c280b416-2fd7-44b3-9af7-cf6f45cbb7c5/video.mp4

## Entry 27
- ID: 14159
- Author: allenlin0728
- Created At: 2026-06-15T03:40:19Z

### Content

After doing some testing with the prototype models that I had, and the servos which arrived, I realized that the servos could not be fitted inside the component, because the wire could not be routed with my current design. So I expanded the slit in the model where the wire could be routed from for ease. I also found out that the mounting for the servo arm should be using m3 screws, and not m2.5, so I redid those mounting holes in CAD. Luckily I had those types of screws lying around, so no extra cost was used.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzI4MDcsInB1ciI6ImJsb2JfaWQifX0=--756b1c1fe0d9229d1f4a4116a1964dd654f57f85/image.png)
Another thing I updated in my cad of the leg was the side of the leg housing, which would interfere with the movement of the servo arm. I solved this by adding a grove on the side, allowing the servo to be rotated all the way without interference. 
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzI4MDgsInB1ciI6ImJsb2JfaWQifX0=--1dce910f29aca5073200e70a680db2f2e744c3c3/image.png)

The last problem that I had to fix was the direction of tips of the legs, where even though the left leg's tpu tip should be good, it's mount for it is wrong, where it is facing a different direction. I fixed this by mirroring the direction of the sketches for the leg tips, which worked out well.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzI4MDksInB1ciI6ImJsb2JfaWQifX0=--fd3c4ceebcd72965e73c76fa4e5a5f65d349abc4/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzI4MTAsInB1ciI6ImJsb2JfaWQifX0=--d366d84e6104dc01221860385e85b2d8a54ee700/image.png)
I also altered the BOM spreadsheet a little, as some of the components I bought were a little different from the ones in the previous BOM, so I added those all in to create a more accurate total. The total funds needed from grants is 692.81 CAD, or roughly 500 USD, which is enough from just the 120 hours that are required from the two of us.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzI4NTQsInB1ciI6ImJsb2JfaWQifX0=--6dff376623fadd3fbbb9b613372324b7f1955a1b/image.png)

When I finshed 3d printing the side mounts i noticed that i didn't actually cad in the inserts to mount the servos in, and when I tried drilling the insert holes out, it cracked. I figured that the actual part was fine, as I used the wrong settings on the drill making it unsuitable for 3d printed parts and a drill bit too large, and that just cadding the insert holes in would be enough.

I also started to test the LED matrix, which I assembled then hooked up to the power bank where we tested it with the raspberry pi 4. However, It only worked after following some code from a tutorial and rewiring it again, which took quite a lot of time. 


### Recording Links

- https://lookout.hackclub.com/api/media/a840cd48-fd43-4f39-bfd5-a03a2da39b51/video.mp4
- https://lookout.hackclub.com/api/media/d514cf1e-9ec1-4e62-805b-44f1d0b28694/video.mp4
- https://lookout.hackclub.com/api/media/3bfb2692-922d-4c74-a9e9-a1cfe7b15dbb/video.mp4
- https://lookout.hackclub.com/api/media/8df52cf9-b56a-46bf-bd01-bdfcf1cb86ea/video.mp4
- https://lookout.hackclub.com/api/media/f445703a-512a-4040-8e63-f5517fbdc1c7/video.mp4
- https://lookout.hackclub.com/api/media/96a985f8-62f1-476f-9a58-934dae39745b/video.mp4

## Entry 28
- ID: 14175
- Author: deez.ducks.ca
- Created At: 2026-06-15T05:34:35Z

### Content

Today I sanded and spray painted a few of the parts we have printed to cover up the layer lines and imperfections  of the 3d print. I also organized all the parts we have on hand into part organizers so building will be much smoother and we will not lose parts and have to replace them. We got the led matrix display working after a few hours as we encountered a few problems which includes wiring the display to the pi, finding a library that was compatible and actually getting a image to display on the matrix. We also spent a few hours fixing the 3d printer as the nozzle had gotten clogged with filament.  
![Untitled 6 (1).PNG](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzM2MzAsInB1ciI6ImJsb2JfaWQifX0=--87e69218474fddfe33745350579f303e03f87c3c/Untitled 6 (1).PNG)


### Recording Links

- https://www.youtube.com/watch?v=7pUh69Jf6yY
- https://www.youtube.com/watch?v=9hQ_gLS9bDk
- https://www.youtube.com/watch?v=U-3WffL-74A
- https://lookout.hackclub.com/api/media/abf4c82c-22f8-47bc-bdc7-16f762714b3a/video.mp4

## Entry 29
- ID: 14651
- Author: allenlin0728
- Created At: 2026-06-16T23:28:07Z

### Content

We decided to borrow our friend's 3d printer to help speed up the printing process, which was an Ender 3. However, it didn't work instantly, and needed some tweaking. I first installed Marlin, which was a modded control system for the Ender which would help adjust some of the settings because of the newer firmware and additional features. The bed level and the home z-offset were very wonky, so I tried to manually set that in the configuration file, however, it only messed up the print, where the nozzle would touch the print bed, so I decided to manually set the bed level. Then I took the bed plate out and then reseated the springs and screws, which would ensure that tuning the would be easier because it was more evenly elevated.. I then used the paper test to level the bed, and then started a test print with it, which would be the top enclosure. However it failed and had some stringing and adhesion problems, so the next print i decided to add glue and adjust the temperature settings, and as of now it is still going smoothly. My main 3d printer also had some issues, most notably with layer shifting. Every time I would try to print the parts for the legs overnight, the print would fail as the entire print would shift to the right a bit. 
![IMG_5102.jpeg](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzQ3NjYsInB1ciI6ImJsb2JfaWQifX0=--9e39a2e0dfc76c373cf0cbc603f23954ec17cd9b/IMG_5102.jpeg)
I searched online for people with similar problems, and turns out the most likely problem was that the belt was tensioned too loose or tight. This meant I had to tune the belt to the recommended 110Hz at 15cm to prevent my prints from failing, which took a while but eventually was done by loosening 4 screws on the back side of the printer, and then setting their positions on a slide, tensioning/loosening the belts. 

I also pushed my changes to my cad on github

### Recording Links

- https://lookout.hackclub.com/api/media/75719a8c-83f6-49d2-87a4-16379e7794de/video.mp4
- https://lookout.hackclub.com/api/media/2273a4bd-e84a-4ccf-9c3a-51e4f85537a4/video.mp4
- https://lookout.hackclub.com/api/media/ab46b595-45a0-4d8a-9f7a-d62f5b2422a1/video.mp4
- https://lookout.hackclub.com/api/media/7cdb4498-41ce-45f9-bc27-405865001d4d/video.mp4
- https://lookout.hackclub.com/api/media/06e5fd0b-da9a-4f13-a17e-cf1d98a563ce/video.mp4

## Entry 30
- ID: 14937
- Author: allenlin0728
- Created At: 2026-06-18T05:32:57Z

### Content

After I printed some of the components of the legs and body,  I took of the supports and sanded them down, which prepared them for spray painting. However, while I was 3d printing something, A print ran out of filament, and I had to go change it. But I accidentally took too long letting the filament in the tube extrude out, which meant that the printer would print a empty layer or two, messing up the 3d print. I had not noticed until I ran the 3d printer for a long time noticing that one of the structures has collapsed. When I stopped the print and took the components out of the bed, only two of them were usuable, a very flat piece belonging to the top of the leg and the middle section, which could pr9obably be joined together with adhesive. I also figured out the cable length needed for the robot beforehand, which was around 400-425mm of jumper wire for the back servos on the arm. Since the servos already came with  300mm of wire, I only needed to solder together 6 male to female cables that are 125 mm long(for extra clearance) to the servos. I also tested out the mounting of the servos and bearings and it looked like it was all okay, with adequate tolerances for them to be friction fit. 
![IMG_5112.jpeg](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzU0NTYsInB1ciI6ImJsb2JfaWQifX0=--36e4b5c9d0fcd12b28d71020b46c9fedd6e08c63/IMG_5112.jpeg)
![IMG_5111.jpeg](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzU0NTcsInB1ciI6ImJsb2JfaWQifX0=--434c9d1c988965843fb0c465dd5ce28cf41b83b1/IMG_5111.jpeg)


### Recording Links

- https://lookout.hackclub.com/api/media/23b38faa-dced-40ec-8d21-fe78adfaa621/video.mp4
- https://lookout.hackclub.com/api/media/e9a04edf-9360-4ffb-96d1-6823effe3fda/video.mp4
- https://lookout.hackclub.com/api/media/a16f32fb-6f98-45a6-83dd-bb6aa18a055e/video.mp4
- https://lookout.hackclub.com/api/media/fb4edfca-ad98-401a-9ffa-9cfecf041473/video.mp4
- https://lookout.hackclub.com/api/media/882be93b-fd71-4fc3-b075-13fab9b89a8e/video.mp4
- https://lookout.hackclub.com/api/media/1980050a-9735-4eca-bc87-a774db4d705e/video.mp4

## Entry 31
- ID: 15150
- Author: allenlin0728
- Created At: 2026-06-19T04:10:40Z

### Content

Today I sanded down a lot of the parts we had printed, mostly sections for the legs, and then applied putty/epoxy on some pieces to repair some of the damage from the supports. We were also able to acquire yet another 3d printer from a friend, a ender 3 v2, which I tuned for PETG and printed a benchy on it, which made it ready to print the side pieces for the body, speedy up our process. After a couple fails over these past few days, we only need to reprint 2 out of the 4 parts for the right legs, and 2 more right legs. 

I also noticed that in my cad, the motors were not all facing the right direction for the middle servo, so I changed it and updated my cad and renders for this. And since the renders were updated, I also updated the zine accordingly and uploaded it to the github.


![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzYwNTIsInB1ciI6ImJsb2JfaWQifX0=--c622ca24a62671e0497384b0a97f0cbb26538f3c/image.png)
![IMG_5114.jpeg](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzYwNTMsInB1ciI6ImJsb2JfaWQifX0=--480977887270bcbce1a2b726d95fc15085700740/IMG_5114.jpeg)


### Recording Links

- https://lookout.hackclub.com/api/media/2c720929-5ad5-437b-963c-9c1faea2037e/video.mp4
- https://lookout.hackclub.com/api/media/18c133de-03a7-4662-a2c2-9ad3c9d5220c/video.mp4
- https://lookout.hackclub.com/api/media/1be21dd5-21bd-4458-9a8f-0fca8aea38fd/video.mp4
- https://lookout.hackclub.com/api/media/6f488001-4fc1-4413-b7e2-cb3f4943d39e/video.mp4
- https://lookout.hackclub.com/api/media/6caa4ac9-2af9-484b-bf46-cd65c5bcfd38/video.mp4

## Entry 32
- ID: 15340
- Author: deez.ducks.ca
- Created At: 2026-06-19T20:56:57Z

### Content

Since we have a large led matrix display for Spooder, we wanted to give it some personality by making a custom eye animation for it. I used pixilart with a 64x32 canvas size which matches the matrix's resolution and created a animated gif that matches the mascot on our zine page. Determining the optimal number of frames and how long they should be displayed was the biggest challenge when animating the screen. 
![eyes.GIF](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzY1MzMsInB1ciI6ImJsb2JfaWQifX0=--66da6fb7e469ad0cf1cb986c54ca6c795c8f4a9a/eyes.GIF)


### Recording Links

- https://lookout.hackclub.com/api/media/0b8e2a46-d49e-4e92-9107-f11c86920189/video.mp4
- https://lookout.hackclub.com/api/media/b96c5770-71f3-4349-a9ca-ee0a16d9a599/video.mp4
- https://lookout.hackclub.com/api/media/db7271ce-7d50-4c3e-9272-f45229d745a3/video.mp4
- https://lookout.hackclub.com/api/media/c3e76322-9602-41d0-a08c-70915af5e929/video.mp4

## Entry 33
- ID: 15347
- Author: deez.ducks.ca
- Created At: 2026-06-19T21:18:44Z

### Content

One of our prints failed where the printer didn't extrude anything for a couple of layers which resulted in the print breaking in half when handling. I attempted to solve this by stitching the two pieces back together using leftover filament and a soldering iron to limited success. I was able to join the two pieces and the connection seemed strong, the tolerances for the bearings and the cut-outs for where the servos attach to the print could not be met so we decided to scrap it.  
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzY1MzgsInB1ciI6ImJsb2JfaWQifX0=--4a1fb8f1e97f96c25506a5959fee976b0154c1a7/image.png)
I also spent some time putting in the heat set inserts for mounting servos and other printed components together with our soldering iron and  spray painted them afterwards. 

Many areas of our prints have large imperfections and holes where the printer made an error or where the supports were. Sanding these areas directly would cause the surface layer to degrade and expose the infill underneath which is highly undesirable. To solve this I used automotive spot putty to fill in the imperfections and after it dried, used a higher grit sandpaper to smooth it out. This yielded a very smooth surface that, when painted, gave the part a highly refined look. 
![IMG_3279.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzY1NDgsInB1ciI6ImJsb2JfaWQifX0=--bbb29366a665b2a8ef4d9283e0891559d164f5bb/IMG_3279.png)


### Recording Links

- https://lookout.hackclub.com/api/media/3b8b7164-2a76-4053-926f-5bbc2091e8ba/video.mp4
- https://lookout.hackclub.com/api/media/2397f458-195c-4ea8-9657-39bbd3164a20/video.mp4
- https://lookout.hackclub.com/api/media/4965ca29-0d46-4bac-90db-4c9f62cf96e0/video.mp4
- https://lookout.hackclub.com/api/media/fbc3cd4b-f417-4df7-b979-d36ef12400fe/video.mp4
- https://lookout.hackclub.com/api/media/ab087cc3-2fae-4f78-bac4-37f97fce64fd/video.mp4
- https://lookout.hackclub.com/api/media/cf2f2279-3410-4a00-af0d-fff422575614/video.mp4

## Entry 34
- ID: 15361
- Author: deez.ducks.ca
- Created At: 2026-06-19T22:13:11Z

### Content

When I uploaded the custom Spooder eye gif to the screen, the background was red even though the gif was exported without a background. After doing some digging, I found that gifs do not store transparency the same way as png's do and the fix was to edit Pillow so it knew which pallet index is  transparent and set them to alpha 0. 
![IMG_3280.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MzY1ODgsInB1ciI6ImJsb2JfaWQifX0=--f7ea03e4aba010b4d22d9a9f1a33c805c8e5040d/IMG_3280.png)


### Recording Links

- https://lookout.hackclub.com/api/media/fda90cc8-3685-4bc4-a655-473c78df6e93/video.mp4

## Entry 35
- ID: 16488
- Author: deez.ducks.ca
- Created At: 2026-07-07T14:33:01Z

### Content

Over a few days, I prepped, painted, and assembled the remainder of the legs of the robot and used contact cement to attach the TPU tips. Finally, the legs were attached to the body, and all the electronics were screwed in (Raspi and Yukon). The power bank and Lipo battery slide into hot-swap compartments. Also started making cable extensions for the servos, as the tip servos do not have long enough wires to reach Yukong. 
![IMG_3326.jpg](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6NDA4NTcsInB1ciI6ImJsb2JfaWQifX0=--ce623b47bf5dde220fb80a54f1abb9de05486805/IMG_3326.jpg)


### Recording Links

- https://lookout.hackclub.com/api/media/c6fec259-a8a9-442b-bcab-046e55344bf6/video.mp4
- https://lookout.hackclub.com/api/media/6a40360b-ccac-4e77-ad23-e3782c60aa73/video.mp4
- https://lookout.hackclub.com/api/media/99a6f1e2-02b7-4650-ae23-26e295d018a6/video.mp4
- https://lookout.hackclub.com/api/media/e33b8bdb-7b92-4c37-a590-2ead18f9aaef/video.mp4
- https://lookout.hackclub.com/api/media/ec859c41-08bc-4fab-8728-b1e40288eaae/video.mp4
- https://lookout.hackclub.com/api/media/e0bb0c31-9192-46de-b6c3-85f784ed1e66/video.mp4
- https://lookout.hackclub.com/api/media/2ec8e805-f578-41e1-bdce-43b5beb95caf/video.mp4

## Entry 36
- ID: 16496
- Author: allenlin0728
- Created At: 2026-07-07T22:18:45Z

### Content

I sanded the new parts with 120 grit sandpaper to remove the highest print lines then moved between a mix of 320 and 400 grit sand paper to smoothen the surface for painting. I started to paint the parts with a coat of primer then matte black spray paint. I also assembled the Yukon by inserting the modules then securing them with screws. 
![Screenshot 2026-07-07 at 4.17.50 PM.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6NDA4NzYsInB1ciI6ImJsb2JfaWQifX0=--229d200dafbb30afa4efb9e5da833a8dc95e08ee/Screenshot 2026-07-07 at 4.17.50 PM.png)


### Recording Links

- https://lookout.hackclub.com/api/media/4e8515e1-842b-4d1c-8b8c-6fe7d26ef205/video.mp4
- https://lookout.hackclub.com/api/media/a1696e64-6fbf-4f25-9dac-62863c450064/video.mp4
- https://lookout.hackclub.com/api/media/1479a85d-c049-4db0-b5f8-40c8ee7941f4/video.mp4
- https://lookout.hackclub.com/api/media/291ab643-83f8-4087-a142-0f69ab7c2d03/video.mp4
- https://lookout.hackclub.com/api/media/9ee2aa5e-ed7c-4284-9588-3aff21b494cf/video.mp4
- https://lookout.hackclub.com/api/media/24c21f8e-306b-40d8-a56c-e4ca537a8b21/video.mp4
- https://lookout.hackclub.com/api/media/f262a63f-6026-4694-ba4d-c68c1f35441e/video.mp4
- https://lookout.hackclub.com/api/media/bdbc4ba8-05f8-4c5f-89c9-5d6e9946e96c/video.mp4
- https://lookout.hackclub.com/api/media/4c8861d0-36d1-4c23-86df-299ad2247261/video.mp4
- https://lookout.hackclub.com/api/media/b365b17a-cef2-4f38-86b1-37bb57bdfe30/video.mp4
- https://lookout.hackclub.com/api/media/20054f1c-eac0-43a0-ba95-1c4292f5ecb4/video.mp4
- https://lookout.hackclub.com/api/media/beb38e6b-7d28-481d-8946-d6371c6a1be5/video.mp4
- https://lookout.hackclub.com/api/media/af407ec4-8793-4fea-99d5-d0ea7bcad82f/video.mp4
