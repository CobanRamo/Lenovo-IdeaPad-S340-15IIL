# Lenovo IdeaPad S340-15IIL IceLake
Lenovo IdeaPad S340-15IIL IceLake with OpenCore<br>
Part Number : 81VW00C4GE



```diff
- Last working Bios version is currently cucn28ww_72ww

```


<img src="/Pictures/Lenovo IdeaPad S340-15IIL IceLake.png" alt="My cool HackBook"/>


In work with a multi boot Oparating System  |°|°|°|°
------------- | ------------- | ------------- | -------------| -------------
Windows  | Windows 10 Pro  | Windows 11 Pro  |  
Linux  | Ubuntu 21.10  |   |
MacOS  | Catalina  | Big Sur  | Monterey| Ventura
ChromeOS  | ChromeOS "Volteer"  |   |

*TPM 2.0 chip is enabled for Windows 11, does not affect MacOS versions.<br>
SecureBoot is disabled but can be enabled and rolled out for OpenCore drivers if needed.


<br>
<br>
<br>

The specs of the machine are:

Specifications  | Details
------------- | -------------
Processor  | Intel Core i7-1065G7 (4C / 8T, 1.3 / 3.9GHz, 8MB)
RAM  | 4GB Soldered DDR4-2666 + 8GB SO-DIMM DDR4-2666 (Total 12GB)
Storage  | 512GB SSD M.2 2280 PCIe 3.0 x4 NVMe
Storage  | 256Gb SSD Sata3 (second added by me)
Graphics  | Integrated Intel Iris Plus Graphics G7
Monitor  | 15.6" FHD (1920x1080) IPS 250 nits Anti-glare
Sound Card  | Smart Sound Technology Audio (ALC 257 layout-ID 11 (0B000000))
Card reader  | Working
Network Card  | BCM94360NG
TouchPad  | Fully Fuctional

There are still a few small blemishes that I haven't been able to solve yet.
see Issues.

<br>
<br>
<br>
<br>



To activate the Debug Bios;

Enter BIOS → disable OneKeyBattery → save and exit. 
Poweroff the laptop. 
Power button to turn on → F2 to enter the normal BIOS → Power button to turn off → then press, moving fast, the following keys in sequence

     F1 → 1 → Q → A → Z
     
     F2 → 2 → W → S → X
     
     F3 → 3 → E → D → C
     
     F4 → 4 → R → F → V
     
     F5 → 5 → T → G → B
     
     F6 → 6 → Y → H → N
     
Turn on the power button → F2 enters the hidden Debug BIOS. 

Then go to;<br>
Advanced → Power & Performance → CPU-Power Management Control → CPU Lock Configuration → CFG Lock → Disabled<br>

Then go to;<br>
Advanced → System Agent (SA) Configuration → Graphic Configuration → DVMT Pre-Allocated Selection → DVMT Pre-Allocated → Set to 160MB<br>

save and exit.<br>

There is a lot of customizable in the Debug Bios, just change the two points CPU-Lock & Graphic DVMT !!!!<br>
With other points you break the system.

<br>
<br>


## <p align="center"> Pictures</p>

  <p align="center"><img src="/Pictures/OpenCore BootMenu1.png" width="700" title="OpenCore Menu"></p>
  <p align="center"><img src="/Pictures/OpenCore BootMenu2.png" width="700" title="OpenCore Menu"></p>
  
    
  ##### <p align="center"> Grub menu only for ChromeOS, Ubuntu is launched directly from OpenCore</p>
  <p align="center"><img src="/Pictures/Grub BootMenu1.png" width="250" title="Grub Menu only for ChromeOS"></p>
  <p align="center"><img src="/Pictures/Ubuntu 21.10.png" width="350" title="Ubuntu 21.10"></p>
     <p align="center"> ChromeOS</p>
  <p align="center"><img src="/Pictures/ChromeOS.png" width="350" title="ChromeOS Volteer"></p>
  <p align="center"><img src="/Pictures/ChromeOS_Panel.png" width="150" title="ChromeOS Volteer"> <img src="/Pictures/ChromeOS_Start.jpg" width="150" title="ChromeOS Volteer"> <img src="/Pictures/ChromeOS_Task.png" width="150" title="ChromeOS Volteer"> <img src="/Pictures/ChromeOS_Version.png" width="150" title="ChromeOS Volteer"></p>
     <p align="center"> Windows 10 & 11 Pro</p>
  <p align="center"><img src="/Pictures/Windows 10 Pro.PNG" width="250" title="Windows 10 Pro"> <img src="/Pictures/Windows 11 Pro.png" width="250" title="Windows 11 Pro"></p>
     <p align="center"> MacOS Catalina, BigSur & Monterey</p>
  <p align="center"><img src="/Pictures/About this Mac Catalina.png" width="250" title="About this Mac"> <img src="/Pictures/About this Mac Big Sur.png" width="250" title="About this Mac"> <img src="/Pictures/About this Mac Monterey.png" width="250" title="About this Mac"></p>


<p align="center"><img src="/Pictures/Graphic.png" width="700" title="Graphic"></p>
<p align="center"><img src="/Pictures/Audio.png" width="700" title="Audio"></p>
<p align="center"><img src="/Pictures/Bluetooth.png" width="700" title="Bluetooth"></p>
<p align="center"><img src="/Pictures/USB.png" width="700" title="USB"></p>
<p align="center"><img src="/Pictures/Batterie.png" width="700" title="Batterie"></p>
<p align="center"><img src="/Pictures/TouchPad.png" width="700" title="TouchPad"></p>

