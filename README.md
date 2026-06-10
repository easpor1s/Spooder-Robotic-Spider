<img width="1920" height="1080" alt="Untitled design" src="https://github.com/user-attachments/assets/ffc46d15-3e6c-4713-acb4-46140ba9873f" />

## What is Spooder?
The first iteration of Spooder is a remote controlled robotic spider companion with 6 legs. It has a led display that projects a face and facial expressions based on the actions it takes. 
At its core, the robot is powered by a 2gb Raspberry Pi 4 connected to a Pimoroni Yukon developement board through UART. The legs use a three jointed, two axis design which allows for a high degree of movement.
On the legs, one servo controls the legs movement along the X axis and two along the Z axis. This design is very similar to the joint of your finger and allows the robot to grab at objects and sweep itself along smoothly. 

<img width="3440" height="1090" alt="f6cd5328-6a3f-467c-9590-b50c2f226232" src="https://github.com/user-attachments/assets/75d1d94f-6b03-4abc-8b7b-c49dd7a5d1c3" />



## How do I interact with Spooder?
The first iteration of Spider will be controlled via a game console controller such as a Xbox gamepad. The left joystick will control the robots front and back movement while the right joystick will control the robots left and right movement. The controller will be 
connected to the robot via bluetooth which keeps hardware requirements simple and reduces our costs. 
Additional functions will be mapped to the controllers shoulder buttons, directional pad, and the ABYX buttons as they are developed. 

## Why does it exist?
Both of us are in the same robotics competition and wanted to try something new. We only built wheeled drivetrains for our Vex bots and any variation in design is still centered around wheels but just in different configurations. 
We decided to try something new so we settled on a walker robot idea that relies on legs with servos instead of wheels with motors. Additionally, with our previous robots, the building and design experience was highly procedural where all the parts came from a standardized catalogue which made the experience feel repetitive. 
This project is our attempt at widening our hardware knowledge base and learning new skills while yielding something meaningful. Both of us have little to no experience with the components and steps we are using in the making of Spooder which is a steep learning curve and why this project is being attempted. 

## What are the future plans of Spooder?
In the future, we aim to have Spooder have the hardware to run a local large language model and be able to track and follow you without human input. 
We also aim for Spooder to be able to react to gestures such as waves, thumbs up, and maybe even give high-fives. In the future, components that will allow the bot to jump up onto or over obstacles may be added through spring or pneumatic systems as well. 

## Librarys
[PIGPIO](https://github.com/joan2937/pigpio) for servo control

## Programs
[Autodesk Fusion](https://www.autodesk.com/uk/products/fusion-360/overview) for CAD

[Canva](https://www.canva.com/) for logo design

## License
[MIT](https://opensource.org/license/mit) License

