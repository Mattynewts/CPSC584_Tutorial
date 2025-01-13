# CPSC584_Tutorial

This github aims to capture all the required material and documentation needed to be successful in Computer Science 584 - Human-Robot Interaction 

We will be using the Sunfounder PiCrawler kit throughout this class: 
https://docs.sunfounder.com/projects/pi-crawler/en/latest/index.html

### Kit requirements:
1. Raspberry Pi (supplied to you)
2. Micro SD card for OS
3. 18650 batteries (you will each be given 2)
   **ensure your batteries are fully charged for step 4 onwards**


# Part 1: Downloading Raspberry Pi OS with EzBlock
**Important - EzBlock will not work if you are using a Raspberry Pi 5**
- If you are using a Raspberry Pi 5 you will need to follow the guide for using python to control the robot
- Everyone will be supplied with a Raspberry Pi 3 so this only applies to you if you have your own

### Download the Software from here:
Use the following guide to install the required OS onto your mircoSD card (https://docs.sunfounder.com/projects/ezblock3/en/latest/quick_guide_3.2/install_ezblock_os.html#install-ezblock-os-latest).

If you choose to set a username and password please **write it down** so you dont forget. Otherwise you will need to start this step again.
As for the Configure Wireless LAN settings leave them blank for now.

Once your OS has been downloaded onto the SD card you can insert it into the Pi and continue.

All the Software Setup Summary can be found in the documentation provided by Sunfounder:
https://docs.sunfounder.com/projects/pi-crawler/en/latest/ezblock/quick_guide_on_ezblock.html


# Part 2: Getting the Raspberry Pi MAC address:
For this class, we will need to add the Raspberry Pi MAC address to the classroom wifi router.

**Once you have completed Part 1 do the following steps to get your MAC address**
1. Connect your Raspberry Pi to a monitor (HDMI), power supply (Micro USB), keyboard, and mouse.
2. If software is correct your Pi should boot up and display the log in prompt in a text style format.
3. Log in using your log in credentials (if you used them).
4. Type "ifconfig" into the command line.
5. You will be given information about your networks.
6. Under the "wlan0" section look for the numbers next to the tag "ether". That is your MAC address.
![MACAddress](https://github.com/user-attachments/assets/3315a668-99e7-423b-a8c6-b64399d74388)

So in my case my Pi's MAC address is b8:27:eb:b1:34:3a


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


# Part 3: Leg Assembly
Once the servo motors have been successfully zeroed you can carefully assemble the legs.
**Take care to not move servo motors once zeroed otherwise you will have to redo the zeroing**


## Key Building Notes:
1. Keep small screws and bolts organized
2. Ensure you correctly zero all servo motors
3. Attach the legs to motors at the correct angle
4. Manage your wires from the motors


# Part 4: Connecting to your robot and sample programs
Using this link: https://docs.sunfounder.com/projects/pi-crawler/en/latest/ezblock/get_start_app.html
1. Install EzBlock application or use the web app
2. Configure wifi/bluetooth on your device and connect to the robot in app.
3. **Calibrate the picrawler motors using this guide** https://docs.sunfounder.com/projects/pi-crawler/en/latest/ezblock/calibrate.html
4. Finally run sample programs and play around with your robot!


# Part 5: Robot "Hello World" Excercise 
Now that you have successfully set up your robot you can start to work on the "Hello World" excercise which can be found in your project handout.






