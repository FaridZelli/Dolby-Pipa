# Dolby Preset for Xiaomi Pad 6 (Pipa)

<picture>
  <source media="(max-width: 768px)" srcset="media/xiaomi-pad-6-speakers-dolby.png">
  <img src="data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" alt="" width="100%" align="center">
</picture>

<picture>
  <source media="(min-width: 769px)" srcset="media/xiaomi-pad-6-speakers-dolby.png">
  <img src="data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" alt="" width="50%" align="right">
</picture>

<br>
<br>
<br>

This is a Lunaris Dolby Manager preset for the Xiaomi Pad 6. It aims to deliver balanced sound throughout everyday use in a variety of form factors.  
  
Currently evaluated on:  
`crDroidAndroid-16.0-20260923-pipa-v12.12`
`NLSound.v4.5.Qcom.Devices`

<picture>
  <!-- spacer -->
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='100%' height='0'></svg>" alt="" width="100%" height="0">
</picture>

## Installation

You'll need:
- A custom ROM with Lunaris Dolby Manager
- [Xiaomi Pad 6 Quad Speakers Preset](https://github.com/FaridZelli/Dolby-Pipa/releases/latest)
- [NLSound](https://github.com/Briclyaz/NLSound) (**strongly recommended**)

<picture>
  <!-- spacer -->
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='100%' height='0'></svg>" alt="" width="100%" height="0">
</picture>

### Part 1
Choose the "Music" profile and import the EQ preset from releases as follows:

<picture>
  <source media="(min-width: 769px)" srcset="media/1.png">
  <img src="data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" alt="" width="40%" align="left">
</picture>

<picture>
  <source media="(min-width: 769px)" srcset="media/2.png">
  <img src="data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" alt="" width="40%" align="left">
</picture>

<picture>
  <!-- spacer -->
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='100%' height='0'></svg>" alt="" width="100%" height="0">
</picture>

<picture>
  <source media="(min-width: 769px)" srcset="media/3.png">
  <img src="data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" alt="" width="40%" align="left">
</picture>

<picture>
  <source media="(min-width: 769px)" srcset="media/4.png">
  <img src="data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" alt="" width="40%" align="left">
</picture>

<picture>
  <source media="(max-width: 768px)" srcset="media/1.png">
  <img src="data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" alt="" width="100%" align="center">
</picture>

<picture>
  <!-- spacer -->
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='100%' height='0'></svg>" alt="" width="100%" height="0">
</picture>

<picture>
  <source media="(max-width: 768px)" srcset="media/2.png">
  <img src="data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" alt="" width="100%" align="center">
</picture>

<picture>
  <!-- spacer -->
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='100%' height='0'></svg>" alt="" width="100%" height="0">
</picture>

<picture>
  <source media="(max-width: 768px)" srcset="media/3.png">
  <img src="data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" alt="" width="100%" align="center">
</picture>

<picture>
  <!-- spacer -->
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='100%' height='0'></svg>" alt="" width="100%" height="0">
</picture>

<picture>
  <source media="(max-width: 768px)" srcset="media/4.png">
  <img src="data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" alt="" width="100%" align="center">
</picture>

### Part 2
Install NLSound with the following configuration:

```
  01 Volume steps count        : Skip
  02 Max volume level          : Skip
  03 Mic sensitivity           : Skip
  04 Audio bit depth           : Skip
  05 Audio sample rate         : Skip
  06 Limiters & DRC disabled   : Skip
  07 Vendor Hi-Fi features     : Skip
  08 Sub-bass & mixer patches  : Skip
  09 build.prop optimizations  : Install
  10 Bluetooth enhancements    : Install
  11 Direct PCM routing        : Install
  12 Audio effects policy      : Partial
  13 Device hardware tweaks    : Skip
  14 Dolby Atmos Hi-Fi profile : Install
  15 ACDB modifications        : Skip
```

<picture>
  <!-- spacer -->
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='100%' height='0'></svg>" alt="" width="100%" height="0">
</picture>

## Credits
- [Lunaris Dolby Manager](https://github.com/Pong-Development/hardware_dolby) by @Ghosuto and @adithya2306  
- [NLSound](https://github.com/Briclyaz/NLSound) by @Briclyaz
