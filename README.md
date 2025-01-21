# CPSC584_Tutorial Documentation

This github aims to capture all the required material and documentation needed to be successful in Computer Science 584 - Human-Robot Interaction 

We will be using the Sunfounder PiCrawler kit throughout this class: 
https://docs.sunfounder.com/projects/pi-crawler/en/latest/index.html

### Kit requirements:
1. Raspberry Pi 3 (supplied to you)
2. Micro SD card for OS
3. 18650 batteries (you will each be given 2)
   **ensure your batteries are fully charged for step 4 onwards**


# Part 1: Downloading Raspberry Pi OS with EzBlock
**Important - EzBlock will not work if you are using a Raspberry Pi 5**
- If you are using a Raspberry Pi 5 you will need to follow the Sunfounder guide for using python to control the robot
- Everyone will be supplied with a Raspberry Pi 3 so this only applies to you if you have your own

### Download the Software from here:
Use the following guide to install the required OS onto your mircoSD card (https://docs.sunfounder.com/projects/ezblock3/en/latest/quick_guide_3.2/install_ezblock_os.html#install-ezblock-os-latest).

If you choose to set a username and password please **write it down** so you dont forget. Otherwise you will need to start this step again.
As for the Configure Wireless LAN settings leave them blank for now.

Once your OS has been downloaded onto the SD card you can insert it into the Pi and continue.


# Part 2: Connecting to Wifi

**UPDATED**
We no longer need to collect the MAC addresses for the Raspberry Pi's

We can now simply connect to the tutorial rooms local wifi using SSID and password.
Please email me once you get to this part so I can securely give you the log in credentials.


# Part 3: Building the robot Head
**Do not build the robot legs yet as we will want to install software and zero motors before doing so**

While we wait for the Raspberry Pi's to be added to the router we can start building. First we will build the robot head using the included instructions with the kit. 
You can use this video if you are having trouble or need a visual reference: 
https://youtu.be/2gxxvL2_hR8?si=bQad0wxxyRabNjkX


# Part 4: Zeroing the Servo Motors
**This step is important to ensure our robot has full functionality after assembly**

Zero the servo motors following steps from the following link (https://docs.sunfounder.com/projects/pi-crawler/en/latest/ezblock/quick_guide_on_ezblock.html -> you can ignore the plug in USB-C part since we are using the older Robot HATs. Just ensure your batteries are charged)

This video also gives a run down of what is needed for this part:
https://youtu.be/2gxxvL2_hR8?t=626


# Part 5: Leg Assembly
Once the servo motors have been successfully zeroed you can carefully assemble the legs using the included guide in the kit.
**Take care to not move servo motors once zeroed otherwise you will have to redo the zeroing**

## Key Building Notes:
1. Keep small screws and bolts organized.
2. Ensure you correctly zero all servo motors.
3. Attach the legs to motors at the correct angle.
4. Manage your wires from the motors.


# Part 6: Connecting to your robot and sample programs
1. Install EzBlock application or use the web app.
2. Use this guide to connect to the robot using your device https://docs.sunfounder.com/projects/ezblock3/en/latest/quick_guide_3.2/connect_product_ezblock.html#connect-product-ezblock-latest.
3. **Calibrate the picrawler motors using this guide** https://docs.sunfounder.com/projects/pi-crawler/en/latest/ezblock/calibrate.html
4. Finally run sample programs and play around with your robot!

For more details visit: https://docs.sunfounder.com/projects/pi-crawler/en/latest/ezblock/get_start_app.html

# Part 7: Robot "Hello World" Excercise 
Now that you have successfully set up your robot you can start to work on the "Hello World" excercise which can be found in your project handout.






