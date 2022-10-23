# macOs-Monterey-on-ryzen-5600x-gt710-msi-x470
MacOS for Ryzen 5600x, MSI X470 Gaming Plus Max and Nvidia GT710

![Screenshot](https://github.com/pronabsen/macOs-Monterey-on-ryzen-5600x-gt710-msi-x470/blob/main/ScreenShot.png)

Configaration: 

AMD Ryzen 5 5600X 6-Core Processor
Family: 19h, Model: 03h
Physical: 6, Logical: 12
L1(Total): 384 KB, L2(Total): 3 MB, L3(Shared): 32 MB

Motherboard: X470 GAMING PLUS MAX (MS-7B79)

Graphics: NVIDIA GeForce GT 710
Memory: 8GB, Storage: 111GB

macOS Version: 12.6
AMDRyzenCPUPowerManagement:
  Version: 0.7.1, CPU Supported: Yes



I hadnt used any kind of MacOS back then, it was first mac os with a Ryzen 5 5600x and GT710. So I thought to give BigSur a try. 
Everything seems to be working fine. Including Sleep. Just remember to add your serial number etc. You know how. 

Performance seems kinda "choppy" and laggy. Especially the animations. 
My GPU is working fine but the AMD mods are not optimized as much. 
Thanks to the devs though for allowing us to get macOS with Ryzen CPUs

Updated OpenCore. Works with 12.5 and the latest BIOS. Just make sure to disable BAR. Also, no Mic but you can use VoodooHDA if you wish. Lastly, DSDT was removed. System wouldnt boot with it
