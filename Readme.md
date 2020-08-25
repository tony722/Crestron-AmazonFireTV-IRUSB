# AET Amazon Fire TV (IRUSB) 1.0.0

This module requires the IRUSB dongle from Video Storm. 
(As of this time this is the only way I'm aware of controling the Amazon Fire TV from Crestron)

This small dongle provides a logic board to enable TCP/IP control. (It also provides IR in/out which is unused in this application.) 

### App Installation:
For this to work, you must install the IRUSB App onto your Amazon Fire TV device from the Amazon app store: https://amzn.to/2Wc4Uyu 
This free app opens the TCP/IP server on port 9093d. (Note: the IRUSB dongle is required for the app to function, even if its IR functionality is unused.)

Purchase the IRUSB dongle from:
https://www.video-storm.com/proddetail.php?prod=IRUSB

### Supported devices (Android v5.1 or later):
- Amazon Fire TV 4K
- Amazon Fire TV Cube
- Amazon Fire
- Amazon Fire Stick
- Amazon Fire Stick 4K
- nVidia Shield Pro

### The following components are also needed:
  For Amazon Fire TV or Fire Stick:
    OTG Adapter Cable: https://amzn.to/2IF0Izw
    Ethernet Adapter (if not using built-in Wifi): https://amzn.to/39JPGF6 
	  (Use this UGREEN adapter if it's available. Many other adapters--for example, the Amazon branded ethernet adapter--do not work with the IRUSB.)

  For Amazon Cube:
    Micro USB Adapter: https://amzn.to/39L7ui
    Ethernet Adapter: https://amzn.to/39JPGF6 
	  (Note: Use this UGREEN adapter if it's available. Many other adapters--for example, the Amazon branded ethernet adapter--do not work with the IRUSB.)

### Connect FireTV_TX$ to a TCP/IP Client
  Port: 9093d

## Download
Use your glt client to clone this repository, or simply [click here to download](https://github.com/tony722/Crestron-AmazonFireTV-IRUSB/archive/master.zip).

## Support
For (paid) support on your installation or custom modifications to this driver, you may contact me via my website:
http://www.iconsultants.net

Hope this is helpful to you,

Tony Evert
