# Asus Prime Z490-A Hackintosh

Hello folks!  
This system is mainly built for music production/mixing and gaming.  
Despite some negative feedback over the internet about Asus boards and some difficulties about the Z490 platform I took a leap of faith and purchased the hardware. So far I had no major troubles, everything seems to work fine.


## HARDWARE:  


    * ASUS PRIME Z490-A (BIOS v.0707)
    * INTEL I7 10700K
    * GSKILL RIPJAWS V 32 GB 3200MHz
    * ASUS STRIX RADEON RX5700 XT
    * XPG SX8200 PRO NVME SSD 512GB (MAC)
    * XPG SX6000 NVME SSD 256GB (WINDOWS)
    * STEINBERG UR22 MKII USB AUDIO INTERFACE
    * FENVI PCI-E WIFI & BLUETOOTH  

## SOFTWARE:

    * OPENCORE v. 0.6.1
    * macOS CATALINA v. 10.15.6
    * WINDOWS 10

## Working: (Everything!)
    * Sleep/Wake
    * Wi-Fi / Bluetooth (OOB, no tweaks)
    * SideCar, Airdrop, HandOff, Facetime, Messages
    * Netflix etc. with Safari on single/dual monitor setup (iMac19,1)
    * iGPU + dGPU (System Report doesn't show iGPU but IOREG. does)
    * Ethernet
    * USB (mapped (currently) or not mapped, always worked, never had a problem... except USB3 external HDD's not detected on SSxx ports, works USB2 speed on HSxx. Flash drives are ok.)
    * Audio is disabled from BIOS, never used it but I know it works. There are several posts about it, should be easy to find.
    * DRM


## Installation:

    After buiding the PC, I installed Windows and updated BIOS. Followed every step carefully with Dortania's guide. Having a Windows install helled a bit. 
    Took almost a day to create the USB installer but it was worth it. Installation was flawless. 
    As a habbit from past, I disable all peripherials from BIOS, remove dGPU and the Windows drive. In time, this proved to be less time consuming.  
    Before I upgraded to 5700XT I had an Asus RX580. It didn't work without CSM enabled because of the cards BIOS. Enabling CSM didn't cause any problems though.  
    Besides this everything was problem free and there's nothing extraordinary to report.

    
    Thanks to everyone in hackintosh community, learned a lot from you people.  
