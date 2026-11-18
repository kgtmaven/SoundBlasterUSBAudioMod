# Sound Blaster USB Audio Drivers Mod

${\color{red}WARNING! \space Use \space At \space Your \space Own \space Risk!}$

Sound Blaster USB Audio Drivers for older devices.

Such as Sound Blaster X-Fi Surround 5.1, Sound Blaster X-Fi Notebook, Sound Blaster X-Fi Go! and etc.

This driver is designed to solve problems that older devices have with newer operating systems and to provide additional features.

<br/><br/>
<img width="608" height="472" alt="294654215-94b22b31-ed95-44cf-9d2b-5fbb8802f859" src="https://github.com/user-attachments/assets/002143f3-ceed-406f-8474-b8605f3992a3" />
<br/><br/>

## Supported Devices
 - Sound Blaster X-Fi Notebook
 - Sound Blaster X-Fi Surround 5.1
 - Sound Blaster X-Fi Go!
 - Sound Blaster Wireless
 - Sound Blaster X-Fi HD / Digital Music Premium HD
 - Sound Blaster X-Fi Surround 5.1 Pro
 - Sound Blaster X-Fi Go! Pro
 - Sound Blaster R3 / Audigy 6 USB

<br/>

## Additional Features
 - 2ch Stereo Output for Sound Blaster X-Fi Notebook.
   - ![sbxnmodstereo](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/3a4771ca-9745-4942-b226-3a6d85878cb9)
   - Sound Blaster X-Fi Notebook originally only supports Virtual 5.1 Surround output. So there is a minor problem in some applications that only support 2ch Stereo. This driver solved this and added 2ch Stereo output.

 - Bass Boost effect for Sound Blaster X-Fi Notebook.
   - ![VirtualBox_Win10_02_02_2024_17_10_02](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/87acaa91-bba0-47c3-a14c-5007c098068c)
   - The Bass Boost effect is a feature supported on all Sound Blaster X-Fi sound cards except the Sound Blaster X-Fi Notebook. I don't know why it isn't supported, but this driver supports the Bass Boost effect just like other Sound Blaster X-Fi sound cards.

 - Dolby Digital Live and DTS Connect Encoder for Sound Blaster X-Fi Surround 5.1
   - ![VirtualBox_Win10_11_02_2024_14_12_38](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/253ce891-345b-4093-9c91-540b14652194)
   - Sound Blaster X-Fi Surround 5.1 (not Pro) does not originally support DDL or DTS Connect. This driver supports these as additional features.
 
 - DTS Neo:PC Decoder for Sound Blaster X-Fi Surround 5.1
   - ![VirtualBox_Win10_11_02_2024_14_13_50](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/74063a89-beb7-4d56-93fc-546b621c7585)
   - This feature is not supported by most other Sound Blaster USB MOD drivers. (Originally, only PCI based Sound Blaster supported this feature.) This driver provides this as an additional feature.

 - SVM (Smart Volume Management) for Sound Blaster X-Fi Surround 5.1
   - ![VirtualBox_Win10_11_02_2024_14_15_25](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/9fd547f0-4c69-497b-b002-3b3245f2ffd1)
   - SVM (Smart Volume Management) effect is a feature supported on all Sound Blaster X-Fi sound cards except the Sound Blaster X-Fi Surround 5.1, I don't know why it isn't supported, but this driver supports the SVM (Smart Volume Management) effect just like other Sound Blaster X-Fi sound cards.

 - SBX Pro Studio / THX TruStudio Pro
   - Now you can use THX TruStudio Pro or SBX Pro Studio effects even on older sound cards!

 - SBX Pro Studio Surround / Dialog Plus for Sound Blaster R3 / Audigy 6 USB
 - <img width="882" height="637" alt="image" src="https://github.com/user-attachments/assets/a7003488-be7f-4b2c-a010-736f6bc941d0" />
 - This hardware does not originally support the 'SBX Pro Studio Surround' and 'SBX Pro Studio Dialog Plus' effect. So I'm implemented some effects using hardware processing for effects that were originally supported, and using software processing for effects that were not originally supported.
 - You can download the modified driver and the modified control panel [here](https://github.com/kgtmaven/SB1540Mod/releases/tag/SB1540).



<br/>

## Notes
 - On Sound Blaster X-Fi Notebook, the current driver's 2ch stereo output mode is limited to 16-bit. To use 24-bit mode, switch the output setting to 5.1 channel output mode, or use the https://github.com/kgtmaven/SoundBlasterUSBAudioLegacyMod driver.
 - To use the Dolby Digital Live and DTS Connect, 'Dolby Digital Live & DTS Connect Pack' Software and additional Activation is required. (KGAs something, do it your self.)
 - When installing the driver, you must boot in 'Disable driver signature enforcement' mode.
