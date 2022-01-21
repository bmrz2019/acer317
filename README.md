# Acer-Aspire-A317

# Acer Aspire 3 (A317-33-P4X1) 

- screen size 17,3" 
- FHD IPS, 
- Pentium N6000, 
- 8GB RAM, 
- 256GB SSD, 
- eshell - (UEFI) - not linux 

##  ```lubuntu-21.04-desktop-amd64.iso``` 

### tldr; everything works 100 %

- Brightness +/-
- Audio (mic + speaker fine)
- Intel Jasper Lake (works well with even 4K youtube videos)
- WiFi Qualcomm Atheros QCA9377 
- Bluetooth and audio
- HDMI (did not test) - have no monitor
- Function keys works fine
- Fan silent most of the time
- Jasper Lake is quick enough for up to 20 tabs
- Hinge is also good
- Webcam fine
- Light enough to keep in table - and stow in drawer in the night.

### Not good

- USB sockets are too difficult (sticky) to put and pull out. Either bad manufacturing or not perfect specs. I have used Thinkpads/ Apple/ Dell latitudes and things just slide in smooth

### Upgrades

- 2 X RAM slots
- 1 X m2 SSD (nvme) (M2.SATA SSD does NOT work)
- No slots or sockets available for adding an extra SSD/HDD
- So much space for 2.5 inch disks. Ideally one could even put inside a USB-3 hub or sacrifice one of the two USB hubs to add a USB SSD.


## References

- For WiFi: Do not use channels 13,14 in your router if you are on 2,4 GHz. It did not work. But all other channels work fine.
- According to this linux mint thread https://forums.linuxmint.com/viewtopic.php?t=351872&p=2032054
- One needs to install ```sudo apt install linux-oem-20.04b``` for jasper lake.
- For me it works out-of-the-box.

> Intel Pentium Silver N6000 is listed as part of the Jasper Lake family and I know the 5.10-oem kernel works to provide the driver from this thread [SOLVED] Jasper Lake graphics driver.

> It is also possible the 5.11 kernel which is now available in Update Manager will also provide the graphics driver, but I am not positive it will.

> I will give you instructions for both of those and you can decide how to help your friend. Mint will boot to the highest number kernel and if the 5.11 kernel does not work, then booting into grub to boot with a lower number kernel and then removing the 5.11 will be necessary. Not really all that difficult, but I leave it to you to assess the skills of your friend and your ability to help them.

> To install the latest 5.10-oem kernel, open a terminal and run sudo apt install linux-oem-20.04b and then reboot for it to become active. That kernel is also available in Synaptic Package Manager.

- Verify with ```inxi -Fxxxrz```

```
Graphics:  Device-1: Intel vendor: Acer Incorporated ALI driver: N/A 
bus ID: 00:02.0 chip ID: 8086:4e71 
Display: server: X.Org 1.20.9 driver: fbdev unloaded: modesetting,vesa 
resolution: 1920x1080~77Hz 
OpenGL: renderer: llvmpipe (LLVM 11.0.0 128 bits) v: 4.5 Mesa 20.2.6 
compat-v: 3.1 
direct render: Yes 
```

- After installing 
> ```inxi -Gx```

```
Graphics:
  Device-1: Intel vendor: Acer Incorporated ALI driver: i915 v: kernel 
  bus ID: 00:02.0 chip ID: 8086:4e71 
  Display: server: X.Org 1.20.9 driver: modesetting unloaded: fbdev,vesa 
  resolution: 1920x1080~60Hz 
  OpenGL: renderer: Mesa Intel UHD Graphics (JSL) v: 4.6 Mesa 20.2.6 
  direct render: Yes 
```

## Images

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/01.png "01")

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/02.png "02")

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/03.png "01")

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/04.png "01")

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/05.png "01")

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/06.png "01")

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/07.png "01")

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/08.png "01")

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/09.png "01")

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/10.png "01")

### Yes it is https://wiki.lxde.org/en/Main_Page

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/11.png "01")

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/12.png "01")

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/13.png "01")

![alt text](https://raw.githubusercontent.com/treble2019/Acer-Aspire-A317-33-P4X1/main/14.png "01")



