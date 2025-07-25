# All you need to install Sensable/Geomatics/3DSystem for haptic device on Windows 10

## installing the legacy i1394 driver

- Get the drivers ```.msi``` in the repository. Double clic on the file to install it. 
- Open the Device Manager and find the i1394 device. Click rigth on it and choose update driver. 
- Choose the on inside the directory dedicated to the i1394 inside in C:\Program_x86.

## Install the Phantom Device Driver

- Get the driver in the repository
- Install it
- Configure your haptic device. Normaly you should get it serial number in the test interfac

## Test your haptic device
- open the Test application
- if legacy driver are well installed, force feedback should work

You have to know that you can use USBC C with adaptator, it works with three adaptators to go to the haptic device in firewire to my USB C on my Mac. However be carreful because i1394 is not managed ofen on only one USB C. 

## Optionnaly you can install VRPN 7.35, using CMake and generating .sln to compile it with Visual Studio Communauty 
