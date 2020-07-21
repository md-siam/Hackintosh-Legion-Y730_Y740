# Lenovo Legion Y730 running macOS Mojave
<p align="justify" >
If you are a windows user and require macOS to learn XCode, then you can transform your windows machine into hackintosh machine. Remember, this tutorial is for educational purpose. I will be not responsible for any damage done to your device while installing macOS. Do at your own risk.
This tutorial is only for Lenovo legion Y730/Y740. Back up your important files before starting. All files, that you require for macOS installation, are available in my GitHub page. So, let’s begin
</p>
<p align="center"><img src="images/macOS.png"></p>


## BIOS Settings:

- Press F2 to get into the BIOS. Match your BIOS setting with the pictures gives below:
  - Configuration: [Photo](https://github.com/md-siam/Hackintosh-Legion-Y730_Y740/blob/master/images/BIOS_1.jpg)
  - Device Configuration: [Photo](https://github.com/md-siam/Hackintosh-Legion-Y730_Y740/blob/master/images/BIOS_2.jpg)
  - Boot: No change
  - Exit: Save the changes and exit from BIOS


## Things that do not works:
<img align="right" src="images/TP-Link%20Archer%20T4U%20AC1300.jpg" height="250">
<p align="justify" >
So far everything is working smoothly, except the Wi-Fi card inside the laptop. With my laptop there is Intel® Wireless-AC 9560 dual band Wi-Fi card, and there is no macOS driver for this Intel 9560 Wifi card. But the <b>Bluetooth</b> inside the Intel card works perfectly. So, in order to enable the Wi-Fi connection, I bought a Tp-Link Archer T4U Wi-Fi adapter. A picture of my WiFi card is given on your right. Driver for this Wi-Fi adapter can be downloaded from <a href="https://www.tp-link.com/uk/support/download/archer-t4u/#Driver">here</a>.
</p>


## Alternative of Archer T4U:
<img align="left" src="images/BCM94352Z.jpg" height="300">
<p align="justify" >
If you want to keep inverything inside your laptop, then Broadcom BCM94352Z Wi-Fi card is the alternative of Tp-Link Archer T4U. But it is expensive if you want to buy it brand new. This card is menufacture my <b>Lenovo</b>. Check for Lenovo branding before you decide to buy any Wi-Fi card.
</p>









## Special Thanks To:
1. [tonymacx86](https://www.tonymacx86.com) for Clover
2. [geekrar](https://www.geekrar.com) for full macOS Mojave DMG file [sharing](https://www.geekrar.com/download-macos-mojave-dmg-file-direct-links/)
3. [ᔕᗩᕼᗩᗷᗩT GEᗰᗷᒪᑌᑎG](https://twitter.com/Goeprulz) for providing his [EFI](https://www.dropbox.com/s/hfy1jwdja3wbj76/EFI_LEGION_Y740_10.14.6_V3.zip?dl=0) folder
4. [ComputerTipsLaiju](https://www.youtube.com/watch?v=57aA8e9YQSg&t=66s) for macOS installation guide


## Intel® Virtualization Technology (Intel® VT)
Many applications use Intel Virtualization Technology to work properly, example like:
1. XAMPP
2. Android Studio
3. Virtual Machine/VMWare
4. etc..

So, after successful macOS installation, enabled "Intel Virtual Technology" from BIOS, and those apps will work perfectly.
