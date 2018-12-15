Our Project is implementing an arrows signs technique on a Raspberry pi and embed it on an RC car to be controlled by the arrows signs to let the car follow these commands.
The project aims to equip standard remote control (RC) car with improved control since commonly used RC car control joystick is replaced with a certain controlling system based on camera.
The camera that is attached to the car enables view from perspective of RC car.
The car should have been controlled by getting a certain input from camera which is arrows directions from a picture.

MECHANICAL SYSTEM:
-The RC-Car mechanical specs:         - Mechanical components:
1. 4 wheels driven.		      1. 4 x Geared DC Motor.		6. 1 x Battery Box.
2. 2 levels of the structure.	      2. 1 x Car Chassis.		7. 1 x on/off switch.
3. Plastic frame.		      3. 4 x Car Tire. 	  
4. 4 rubber wheels.		      4. 4 x Speed Encoder.
5. Weighs 500 grams		      5. 8 x Fastener.

You will find the assembled Rc car online and can buy it from “Makers Electronics” shop.
“ https://makerselectronics.com/product/4wd-simple-robot-chassis-kit “

-3D printed components:
1. Raspberry Pi 3 Model case (You can find the CAD files of this case through the following link: “ https://www.thingiverse.com/thing:922740 “)
2. Pi Camera stand (You can find its CAD file through this link: “https://www.thingiverse.com/thing:239391?fbclid=IwAR2CAAjij_6TeNLyZaEpRAr8giY76TLWdbHNzsMBmbgDwkXXWhy4XQcI0Vo “)

ELECTRICAL SYSTEM:
-The RC-Car electrical components:
1. Raspberry Pi 3, Model B/B+
2. Raspberry Pi Camera Board – V2 (8MP)
3. Arduino UNO
4. 2 x L298 Motor Driver Module
5. Power bank
6. 4 x 1.5 volt – AA batteries
7. Raspberry Pi power cable
8. Jumpers

Electrical schematic link:
https://drive.google.com/file/d/1kb8cADRaIxeFCe8IrXmOAxbkiBZ80QDX/view?usp=sharing

*Hint:
- We are using Arduino to control the DC-motors through the PWM signal pins in the Arduino board, as the Raspberry Pi have only one PWM signal pin. We need 4 PWM signal pins to control the 4 DC Motors.
- This power bank will supply the Raspberry Pi only, as to isolate it from the rest of the electrical circuit components to guarantee the Raspberry Pi protection.

Electrical system problems:
1. The batteries weren’t enough to start the system, because we bought low-quality batteries.
2. We decided to use a 12-volt lead acid battery, which was put away from the car and with a 3-meters wire, it was connected to the electrical system of the RC-Car and supplied it with 12-   volt, which isn’t dangerous and totally safefor the electrical system, as shown in figure 15.

Raspberry Pi initialization:
1. You should bring the Raspberry Pi.
2. You should bring a 16 GB memory card.
3. You should bring the Raspberry Pi power cable.
4. Now, if you have all the things in figure 17, then you are ready.
5. You will follow a playlist on YouTube channel
   with an expert, who will make it easy for you to
   initialize Raspberry Pi.
6. Don’t forget to bring the Arduino with you.
7. You should continue with the videos, until you reach the video, where he teaches you how to connect the Arduino with the Raspberry Pi by the codes. You will be able to write an Arduino code    and control the Arduino UNO from a familiar python code. You will be able to do it with some additional code lines to make it compatible to communicate with the Arduino and control it    easily and smoothly.
  Here’s the link of the playlist:
  “https://www.youtube.com/watch?v=RlUhDUJfTe8&list=PLNnwglGGYoTvy37TSGFlv-aFkpg7owWrE “
8. After you finished the last playlist, you can run any code on the Arduino, and you got familiar with Pi Camera.


- Now, you should install the OpenCV library on the Raspberry Pi.
- You should follow the steps in the following link as to install and be familiar with the OpenCV library.
The link:
“ https://www.pyimagesearch.com/2017/09/04/raspbian-stretch-install-opencv-3-python-on-your-raspberry-pi/?fbclid=IwAR0fRES2g5GX5TX4-_FrsbZje92ClGKJ-ZBvShrHWfi6iBHhGP9zJqrcggA “
- Now, you are ready to run any code based on the OpenCV concept, maybe you miss some libraries, but it’s not a big deal. You can solve any error using some of these websites:
1. https://www.pyimagesearch.com/
2. https:// github.com/
3. https://stackoverflow.com/
4. http://answers.opencv.org/questions/
5. https://docs.opencv.org/3.1.0/index.html

The Inputs for the Pi Camera will be arrows signs as shown in link below.
https://drive.google.com/drive/folders/10CLGbFcDN0dmNCjVXouHE12LwA7OqXyw?usp=sharing

NOTE: The 2 uploaded codes are supposed to be processed/run simultaneously. (Code1: Actuation.py, Code2:Processing.py)

