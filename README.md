# Hacked Intel 14.34.4.4964 drivers for Win2K & WinXP
This is a slightly hacked Intel chipset/graphics driver which took me about a couple of minutes to make. The driver has custom resolution support which works great under Windows 2000 (see display instructions and disclaimer for more details)

## Instructions
You must be on Windows 2000 or Windows XP in order to install this driver.

### Install Instructions

1. Clone or download the repo, unzip and click Setup.exe
2. Follow the instructions from the setup program
3. Restart. The driver should be installed and working by then

### Display Instructions
To do

## Supported Chipsets
- Intel(R) 4 Series Internal Chipset
- Intel(R) 82945G Express Chipset Family
- Intel(R) 946GZ Express Chipset Family
- Intel(R) G33/G31 Express Chipset Family
- Intel(R) G35 Express Chipset Family
- Intel(R) G41 Express Chipset
- Intel(R) G45/G43 Express Chipset
- Intel(R) G965 Express Chipset Family
- Intel(R) Q33 Express Chipset Family
- Intel(R) Q35 Express Chipset Family
- Intel(R) Q45/Q43 Express Chipset
- Intel(R) Q965/Q963 Express Chipset Family
- Mobile Intel(R) 4 Series Express Chipset Family
- Mobile Intel(R) 945 Express Chipset Family
- Mobile Intel(R) 965 Express Chipset Family

## Disclaimer
Since the inf file of this driver has been modified it will break WHQL compliance. It might also be buggy for some computers, but it's generally quite stable on my end. If you do encounter bugs or crashes, report them to the issues section. Also not sure if HDMI will work with this driver

This was tested on a Dynabook-Toshiba Satellite M105-S3041 laptop running Windows 2000 Service Pack 4 (with hfslip and Extended Kernel 3.0 patches) using a Samsung C27F396FH monitor. Its maximum resolution can be set to 1920x1080p 60hz using VGA/analog output
