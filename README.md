# OpenCore-Themes
Themes For OpenCore v0.6.6

- Thanks to [chris1111](https://github.com/chris1111/) for Icnspack-Builder
- Thanks to [OpenCore Team](https://github.com/acidanthera/OpenCorePkg) for OpenCore

## Themes
* Big Sur
* Dark
* Big Sur - Dark Icons
* Light
* Sharp (Dark/Light)
* Smooth (Dark/Light)
* Sharp - B
* Smooth - B
* DarkSharp - B
* DarkSmooth - B

## Custom Icons Included
* Linux icons (Dark/Light/Sharp/Smooth)

### Download
* Head to [Release](https://github.com/LuckyCrack/OpenCore-Themes/releases/tag/v1.2) page. 

### Setup
* Replace EFI > OC > Resources 

### config.plist
* Misc > Boot > PickerVariant: Auto

### Custom Icon Setup (Linux icon etc.)
*  Misc > Boot > PickerAttribute: 1
*  Place the icon(eg. Linux-Dark.icns) in the Root Directory of the Drive
*  Rename it to ".VolumeIcon.icns"
-  For APFS file systems 
   * Mount "Preboot" and add the ".VoumeIcon.icns" at Preboot volume in per-volume directory (/System/Volumes/Preboot/{GUID}/ when mounted at default location within macOS)
* More Info [Here](https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf) See Section 8.3 Boot Properties > 6. PickerAttributes

## Preview
### Big Sur
![Big-Sur](https://github.com/LuckyCrack/OpenCore-Themes/blob/main/Preview-BS.png)

### Dark
![Dark](https://github.com/LuckyCrack/OpenCore-Themes/blob/main/Preview-D.png)

### Big Sur Dark
![Big-Sur-Dark](https://github.com/LuckyCrack/OpenCore-Themes/blob/main/Preview-D-BS.png)

### Light
![Light](https://github.com/LuckyCrack/OpenCore-Themes/blob/main/Preview-L.png)

### Sharp
![Sharp](https://github.com/LuckyCrack/OpenCore-Themes/blob/main/Preview-S.png)

### Smooth
![Smooth](https://github.com/LuckyCrack/OpenCore-Themes/blob/main/Preview-SM.png)

### Sharp Dark
![Sharp](https://github.com/LuckyCrack/OpenCore-Themes/blob/main/Preview-S-D.png)

### Smooth Dark
![Smooth](https://github.com/LuckyCrack/OpenCore-Themes/blob/main/Preview-SM-D.png)

### Sharp - B
![Sharp](https://github.com/LuckyCrack/OpenCore-Themes/blob/main/Preview-S-B.png)

### Smooth - B
![Smooth](https://github.com/LuckyCrack/OpenCore-Themes/blob/main/Preview-SM-B.png)

### DarkSharp - B
![Sharp](https://github.com/LuckyCrack/OpenCore-Themes/blob/main/Preview-S-B-D.png)

### DarkSmooth - B
![Smooth](https://github.com/LuckyCrack/OpenCore-Themes/blob/main/Preview-SM-B-D.png)


