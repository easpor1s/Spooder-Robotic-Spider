<img width="1410" height="2000" alt="Spooder Zine (1)" src="https://github.com/user-attachments/assets/e1f0e386-ea0e-4f12-bbfe-5a1cabe41768" />



## What is Spooder?
The first iteration of Spooder is a remote controlled robotic spider companion with 6 legs. It has a led display that projects a face and facial expressions based on the actions it takes. 
At its core, the robot is powered by a 2gb Raspberry Pi 4 connected to a Pimoroni Yukon developement board through UART. The legs use a three jointed, two axis design which allows for a high degree of movement.
On the legs, one servo controls the legs movement along the X axis and two along the Z axis. This design is very similar to the joint of your finger and allows the robot to grab at objects and sweep itself along smoothly.

<img width="2560" height="1227" alt="2" src="https://github.com/user-attachments/assets/485091fc-6f9e-4173-8694-b13f6f4aebc0" />

## How do I interact with Spooder?
The first iteration of Spider will be controlled via a game console controller such as an Xbox gamepad. The left joystick will control the robots front and back movement, while the right joystick will control the robots left and right movement. The controller will be 
connected to the robot via a 2.4ghz dongle, which keeps hardware requirements simple and reduces our costs. Using a controller with a dongle also eliminates Bluetooth pairing problems, which can be frustrating to troubleshoot. 
Additional functions will be mapped to the controller's shoulder buttons, directional pad, and the ABYX buttons as they are developed. The controller we are using is a 8BitDo Ultimate 2C game pad which has good buld quality and is very affordable. Spooder requires python 3.9 or newer, PIGPIO for controlling servos, and pygame. 

## Why does it exist?
Both of us are in the same robotics competition and wanted to try something new. We only built wheeled drivetrains for our Vex bots and any variation in design is still centered around wheels but just in different configurations. 
We decided to try something new, so we settled on a walker robot idea that relies on legs with servos instead of wheels with motors. Additionally, with our previous robots, the building and design experience was highly procedural where all the parts came from a standardized catalogue which made the experience feel repetitive. 
This project is our attempt at widening our hardware knowledge base and learning new skills while yielding something meaningful. Both of us have little to no experience with the components and steps we are using in the making of Spooder which is a steep learning curve and why this project is being attempted. 

## What are the future plans of Spooder?
In the future, we aim to have Spooder have the hardware to run a local large language model and be able to track and follow you without human input. 
We also aim for Spooder to be able to react to gestures such as waves, thumbs up, and maybe even give high-fives where it will raise on of its legs to tap your hand. In the future, components that will allow the bot to jump up onto or over obstacles may be added through spring or pneumatic systems as well. 

## Instructions
Because the models and enclosure is split into multiple components, assembly can be quite tricky.
- 3d print all models with petg or CF-petg except for the leg tips, which should use TPU.
- Add appropriate brass inserts and bearings, which should be heat set and friction fit appropriately
- Sand down joints if needed
- Assemble left and right legs, and mount the body servo arm to the top part of the legs
- Attach the motors to the mounts on the body, and then attach the leg assembly to them.
- Add electronics to the baseplate, and the LED matrix to the top enclosure
- Wire all components and add power supply and power bank
- Assemble all components together, the leg mounts, guards and top enclosure to the baseplate
## Setting up code
To set up code, first make sure all hardware dependencies are met. You will need a Pimoroni Yukon with 5 servo modules attached, a USB-A to USB-C cable running from the Raspberry Pi to the Yukon, a gamepad dongle plugged into the pi and your gyro connected to the pi through i2c as well. On the software side, you must have Python 3.9 and the Pigpio system on the Pi. 

PowerShell:

powershell -ExecutionPolicy Bypass -File .\deploy.ps1 -PiHost "your_pi_ip" -PiUser "your username"

Raspi Terminal:

Setup Environment:

ssh your_username@your_pi_ip_here cd /home/your_username/hexapod chmod +x setup_pi.sh ./setup_pi.sh 

Install sys dependancies:

sudo apt-get update
sudo apt-get install python3 python3-pip python3-venv pigpio python3-pigpio git -y
sudo systemctl enable --now pigpiod

Install Libraries:

cd /home/your_username/hexapod source venv/bin/activate pip install --upgrade pip setuptools wheel pip install pygame pyyaml pip install --no-cache-dir adafruit-circuitpython-lsm6ds 

Run controller: 

sudo /home/your_username/hexapod/venv/bin/python3 /home/spooder/hexapod/main.py 


## Librarys
[PIGPIO](https://github.com/joan2937/pigpio) for servo control

[pygame](https://github.com/pygame/pygame)

## Programs
[Autodesk Fusion](https://www.autodesk.com/uk/products/fusion-360/overview) for CAD design

[Canva](https://www.canva.com/) for graphic design

## License
[MIT](https://opensource.org/license/mit) License

## Circuit diagram
[CirkitDesigner](https://app.cirkitdesigner.com/project/475be11a-6594-4d5f-bd77-2635c9dc39ba)
<img width="1751" height="1095" alt="Spooder Wiring" src="https://github.com/user-attachments/assets/42cd0fe6-0a23-4690-99c1-62cec3086c6b" />


<img width="2560" height="1227" alt="3" src="https://github.com/user-attachments/assets/031dd07c-b1de-48d0-ba9e-ce9b575e8d68" />
<img width="2160" height="1082" alt="5" src="https://github.com/user-attachments/assets/42a443d3-d3fa-4b82-a32f-4b9db4513439" />
<img width="2160" height="1082" alt="4" src="https://github.com/user-attachments/assets/7e3f396a-3d70-46d0-b59f-e0b4bf5ef701" />

