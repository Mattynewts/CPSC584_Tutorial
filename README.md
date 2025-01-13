# CPSC584_Tutorial

This github aims to capture all the required material and documentation needed to be successful in Computer Science 584 - Human-Robot Interaction 

We will be using the Sunfounder PiCrawler kit throughout this class: 
https://docs.sunfounder.com/projects/pi-crawler/en/latest/index.html


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



# Part 1: Building the robot Head
**Do not build the robot legs yet as we will want to install software and zero motors before doing so**

Before we can do any coding we need to first build the robot head. Start using the included instructions with the kit. 
You can use this video if you are having trouble or need a reference visual: 
https://youtu.be/2gxxvL2_hR8?si=bQad0wxxyRabNjkX



# Part 2: Using EzBlock Application to Control the Robot

## Software Setup Summary:
1. Install EzBlock OS to a micro SD card (https://docs.sunfounder.com/projects/ezblock3/en/latest/quick_guide_3.2/install_ezblock_os.html#install-ezblock-os-latest)
2. Zero the servo motors following steps from the following link (https://docs.sunfounder.com/projects/pi-crawler/en/latest/ezblock/quick_guide_on_ezblock.html -> you can ignore the plug in USB-C part since we are using the older Robot HATs. Just ensure your batteries are charged)


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






