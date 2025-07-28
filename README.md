# All you need to install Sensable/Geomatics/3DSystem for haptic device on Windows 10

## Install the legacy i1394 driver

- Get the drivers ```.msi``` in the repository. Double clic on the file to install it. 
- Open the Device Manager and find the i1394 device, righ click on it and update driver.
- Choose manually the driver in ```C:\Program Files (x86)\1394 OHCI Compliant Host Controller (Legacy)\x64_driver\Legacy1394.inf```
- Normally the driver will be set up, and the name of the driver should by '(legacy)' at the end
  
## Install the Phantom Device Driver
- Get the driver in the repository
- Install it
- Configure your haptic device with the Configuration application. Normaly you should get it serial number in the haptic interface.

## Test your haptic device
- Open the Test application
- If legacy driver are well installed, force feedback should work

## Firewire and USB C
You have to know that you can use USB C with adaptator, it works with three adaptators to go from the haptic device in firewire to my USB C on my Mac/PC under Windows 10. However be carreful because i1394 is often managed only on one USB C. 

## Test the Open Haptic Library with the device
You can test all the application provided by the 3DSystem before programming your own application.

## VRPN and Open Haptic
Optionnaly you can install VRPN 7.35, using CMake and generating .sln to compile it with Visual Studio Communauty 2022
