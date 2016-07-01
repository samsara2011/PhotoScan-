# Chapter 1. Installation
## System requirements
#### Minimal configuration
+ Windows XP or later (32 or 64 bit), Mac OS X Snow Leopard or later, Debian / Ubuntu (64 bit)
+ Intel Core 2 Duo processor or equivalent
+ 2GB of RAM
#### Recommended configuration
+ Windows XP or later (64 bit), Mac OS X Snow Leopard or later, Debian / Ubuntu (64 bit)
+ Intel Core i7 processor
+ 12GB of RAM
The number of photos that can be processed by PhotoScan depends on the available RAM and reconstruction parameters used. Assuming that a single photo resolution is of the order of 10 MPx, 2GB
RAM is sufficient to make a model based on 20 to 30 photos. 12GB RAM will allow to process up to 200-300 photographs.
## OpenCL acceleration
PhotoScan supports accelerated geometry reconstruction due to exploiting of the graphics hardware (GPU).
#### NVidia
  GeForce 8xxx series and later.
#### ATI
  Radeon HD 5xxx series and later.
PhotoScan allegedly is able to utilize processing power of any OpenCL enabled device, provided that OpenCL drivers for the device are properly installed. However, due to the large number of various
combinations of video chips, driver versions and operating systems, we are unable to test and guarantee PhotoScan's compatibility with every device and on every platform.

The table below lists currently supported devices (on Windows platform only). We will pay particular attention to possible problems with PhotoScan running on these devices.

####Table 1.1. Supported Desktop GPUs on Windows platform.
NVIDIA AMD
GeForce GTX 680 Radeon HD 7970
GeForce GTX 580 Radeon HD 6970
GeForce GTX 570 Radeon HD 6950
GeForce GTX 560 Radeon HD 6870
GeForce GTX 480 Radeon HD 5870
GeForce GTX 470 Radeon HD 5850
GeForce GTX 465 Radeon HD 5830
GeForce GTX 285
GeForce GTX 280

Although PhotoScan is supposed to be able to utilize other GPU models and on other operating systems than Windows, we do not guarantee that it will work correctly.
###Note
+ OpenCL acceleration can be enabled using OpenCL tab in the Preferences dialog box.
+ Using OpenCL acceleration with mobile video chips is not recommended because of the low performance of mobile GPUs.
##Installation procedure
###Installing PhotoScan on Microsoft Windows
To install PhotoScan on Microsoft Windows simply run the downloaded msi file and follow the instructions.
###Installing PhotoScan on Mac OS X
Open the downloaded dmg image and drag PhotoScan application to the desired location on your hard drive.
###Installing PhotoScan on Debian/Ubuntu
Unpack the downloaded archive with a program distribution kit to the desired location on your hard drive.
Start PhotoScan by running photoscan.sh script from the program folder.
###Restrictions of the Demo mode
Once PhotoScan is downloaded and installed on your computer you can run it either in the Demo mode or in the full function mode. At every run until you enter a serial number it will show a registration box
offering two options: (1) use PhotoScan in the Demo mode or (2) enter the serial number to confirm the purchase. The first choice is set by default, so if you are still exploring PhotoScan click the Continue button
and PhotoScan will start in the Demo mode.

The employment of PhotoScan in the Demo mode is not time limited. Several functions, however, are not available in the Demo mode. These functions are the following:
• saving the project;
• exporting reconstruction results (you can only view a 3D model on the screen).

To use PhotoScan in the full function mode you have to purchase it. On purchasing you will get the serial number to enter into the registration box on starting PhotoScan. Once the serial number is entered the
registration box will not appear again and you will get full access to all functions of the program.
