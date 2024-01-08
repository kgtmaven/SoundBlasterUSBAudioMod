# Sound Blaster USB Audio Drivers Mod

Sound Blaster USB Audio Drivers for older devices.

Such as Sound Blaster X-Fi Surround 5.1, Sound Blaster X-Fi Notebook, Sound Blaster X-Fi Go! and etc.

This driver is designed to solve problems that older devices have with newer operating systems and to provide additional features.

<br/><br/>
![sbxnmod](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/94b22b31-ed95-44cf-9d2b-5fbb8802f859)
<br/><br/>

## Supported Devices
 - Sound Blaster X-Fi Notebook
 - Sound Blaster X-Fi Surround 5.1
 - Sound Blaster X-Fi Go!

<br/>

## Additional Features
 - 2ch Stereo Output for Sound Blaster X-Fi Notebook.
   - ![sbxnmodstereo](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/3a4771ca-9745-4942-b226-3a6d85878cb9)
   - Sound Blaster X-Fi Notebook originally only supports Virtual 5.1 Surround output. So there is a minor problem in some applications that only support 2ch Stereo. This driver solved this and added 2ch Stereo output.
     
 - Dolby Digital Live and DTS Connect Encoder for Sound Blaster X-Fi Surround 5.1
   - ![VirtualBox_Win10_06_01_2024_14_37_40](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/1362955d-27a0-4e4f-8144-f0128f34125a)
   - Sound Blaster X-Fi Surround 5.1 (not Pro) does not originally support DDL or DTS Connect. This driver supports these as additional features.

 - Sound Blaster X-Fi MB2
   - because newer KSAPO will conflict with Sound Blaster X-Fi Notebook.

 - THX TruStudio Pro
   - This is part of the Sound Blaster X-Fi MB2. so i implemented it together.



<br/>

## Current Work in Progress
  - DTS Neo:PC Decoder
    - ![VirtualBox_Win10_08_01_2024_12_47_08](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/2b82fe5d-d1d6-4486-8d2a-b290b0721654)
    - I'm currently working hard to implement this, but it cannot be offered as an additional features at this moment as it conflicts with X-Fi CMSS-3D.


## Notes
 - To use the Sound Blater X-Fi MB2 and THX TruStudio Pro, additional Activation is required. (KGAs something, do it your self.)
 - To use the Dolby Digital Live and DTS Connect, 'Dolby Digital Live & DTS Connect Pack' Software and additional Activation is required. (KGAs something, do it your self.)
 - When installing the driver, you must boot in 'Disable driver signature enforcement' mode.
