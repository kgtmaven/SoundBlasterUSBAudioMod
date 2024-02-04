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
 - Sound Blaster Wireless

<br/>

## Additional Features
 - 2ch Stereo Output for Sound Blaster X-Fi Notebook.
   - ![sbxnmodstereo](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/3a4771ca-9745-4942-b226-3a6d85878cb9)
   - Sound Blaster X-Fi Notebook originally only supports Virtual 5.1 Surround output. So there is a minor problem in some applications that only support 2ch Stereo. This driver solved this and added 2ch Stereo output.

 - Bass Boost effect for Sound Blaster X-Fi Notebook.
   - ![VirtualBox_Win10_02_02_2024_17_10_02](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/87acaa91-bba0-47c3-a14c-5007c098068c)
   - The Bass Boost effect is a feature supported on all Sound Blaster X-Fi sound cards except the Sound Blaster X-Fi Notebook. I don't know why it isn't supported, but this driver supports the Bass Boost effect just like other Sound Blaster X-Fi sound cards.

 - Dolby Digital Live and DTS Connect Encoder for Sound Blaster X-Fi Surround 5.1
   - ![VirtualBox_Win10_09_01_2024_02_29_24](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/5ac239fc-ef51-412d-bc27-182cc61f0349)
   - Sound Blaster X-Fi Surround 5.1 (not Pro) does not originally support DDL or DTS Connect. This driver supports these as additional features.
 
 - DTS Neo:PC Decoder for Sound Blaster X-Fi Surround 5.1
   - ![VirtualBox_Win10_09_01_2024_02_32_44](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/10fb011b-fb59-45a1-a50b-5dc1ef442bda)
   - This feature is not supported by most other Sound Blaster USB MOD drivers. (Originally, only PCI based Sound Blaster supported this feature.) This driver provides this as an additional feature.

 - Sound Blaster X-Fi MB2
   - because newer KSAPO will conflict with Sound Blaster X-Fi Notebook.

 - THX TruStudio Pro
   - This is part of the Sound Blaster X-Fi MB2. so i implemented it together.



<br/>

## Current Work in Progress
  - SBX Pro Studio Surround for Sound Blaster R3 / Audigy 6 USB

    - ![sb1540_mod](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/654e51ba-b5e4-4f59-8052-5b6754effadc)
    - This hardware does not originally support the 'SBX Pro Studio Surround' effect. So I'm implementing some effects using hardware processing for effects that were originally supported, and using software processing for effects that were not originally supported. Like the X-Fi Notebook.

<br/>

## Notes
 - To use the Sound Blater X-Fi MB2 and THX TruStudio Pro, additional Activation is required. (KGAs something, do it your self.)
 - To use the Dolby Digital Live and DTS Connect, 'Dolby Digital Live & DTS Connect Pack' Software and additional Activation is required. (KGAs something, do it your self.)
 - When installing the driver, you must boot in 'Disable driver signature enforcement' mode.
