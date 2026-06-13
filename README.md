<img width="4405" height="6250" alt="Spooder Zine Page" src="https://github.com/user-attachments/assets/4c914eff-6c2b-49e5-b831-8bbfb7176893" />


## What is Spooder?
The first iteration of Spooder is a remote controlled robotic spider companion with 6 legs. It has a led display that projects a face and facial expressions based on the actions it takes. 
At its core, the robot is powered by a 2gb Raspberry Pi 4 connected to a Pimoroni Yukon developement board through UART. The legs use a three jointed, two axis design which allows for a high degree of movement.
On the legs, one servo controls the legs movement along the X axis and two along the Z axis. This design is very similar to the joint of your finger and allows the robot to grab at objects and sweep itself along smoothly.

<img width="2560" height="1082" alt="spooder_2026-Jun-12_09-50-29PM-000_CustomizedView16624897102" src="https://github.com/user-attachments/assets/4d438c52-7ed9-4b4f-bfc6-06201ae9b604" />

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

## Setting up code
To set up code, first make sure all hardware dependencies are met. You will need a Pimoroni Yuking with 5 servo modules attached, a USB-A to USB-C cable running from the Raspberry Pi to the Yukon, a gamepad dongle plugged into the pi and your gyro connected to the pi through i2c as well. On the software side, you must have Python 3.9 and the Pigpio system on the Pi. 

PowerShell:

powershell -ExecutionPolicy Bypass -File .\deploy.ps1 -PiHost "your_pi_ip_here" -PiUser "your username"

Raspi Terminal:

Setup Environment:

ssh your_username@your_pi_ip_here cd /home/your_username/hexapod chmod +x setup_pi.sh ./setup_pi.sh 

Install sys dependancies:

sudo apt-get update
sudo apt-get install python3 python3-pip python3-venv pigpio python3-pigpio git -y
sudo systemctl enable --now pigpiod

Install Libraries

cd /home/your_username/hexapod source venv/bin/activate pip install --upgrade pip setuptools wheel pip install pygame pyyaml pip install --no-cache-dir adafruit-circuitpython-lsm6ds 

Run controller: 

sudo /home/your_username/hexapod/venv/bin/python3 /home/spooder/hexapod/main.py 


## Librarys
[PIGPIO](https://github.com/joan2937/pigpio) for servo control

[pygame](https://github.com/pygame/pygame)

## Programs
[Autodesk Fusion](https://www.autodesk.com/uk/products/fusion-360/overview) for CAD

[Canva](https://www.canva.com/) for graphic design

## License
[MIT](https://opensource.org/license/mit) License

##

<img width="2560" height="1082" alt="spooder_2026-Jun-12_03-33-17AM-000_CustomizedView14989865191" src="https://github.com/user-attachments/assets/4ae8d033-5426-46f3-b79d-cc33bd51912d" />

<img width="2560" height="1082" alt="spooder_2026-Jun-12_03-34-23AM-000_CustomizedView12326146163" src="https://github.com/user-attachments/assets/f7218ef7-9364-4a14-9654-8635a22a3805" />

<img width="2560" height="1082" alt="spooder_2026-Jun-12_03-38-04AM-000_CustomizedView1378896069" src="https://github.com/user-attachments/assets/9b88b611-0174-4437-817d-ab47e9320f6b" />

<img width="2560" height="1082" alt="spooder_2026-Jun-12_03-49-51AM-000_CustomizedView15966012020" src="https://github.com/user-attachments/assets/b154f765-a987-4165-9e39-be1e5c144866" />
