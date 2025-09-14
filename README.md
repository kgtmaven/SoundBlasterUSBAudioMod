# Sound Blaster USB Audio Drivers Mod

Sound Blaster USB Audio Drivers for older devices.

Such as Sound Blaster X-Fi Surround 5.1, Sound Blaster X-Fi Notebook, Sound Blaster X-Fi Go! and etc.

This driver is designed to solve problems that older devices have with newer operating systems and to provide additional features.

<br/><br/>
<img width="1323" height="707" alt="sbx" src="https://github.com/user-attachments/assets/6c12ec45-7029-425b-94b5-a91fc4066506" />
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

 - Sound Blaster X-Fi MB2
   - because newer KSAPO will conflict with Sound Blaster X-Fi Notebook. and it was implemented to use the X-Fi effects on sound cards that do not support the X-Fi effects.

 - Sound Blaster Cinema
   - It is implemented for SBX Pro Studio effects. You can install and use the Sound Blaster Cinema control panel, but the THX TruStudio Pro control panel is still available. The same effect is applied with the THX TruStudio Pro control panel as with the SBX Pro Studio. I don't recommend installing the Sound Blaster Cinema control panel because it conflicts with some sound cards. (e.g. Sound Blaster R3 / Audigy 6 USB and etc.) Therefore, I recommend using the THX TruStudio Pro control panel.

 - THX TruStudio Pro for Sound Blaster R3 / Audigy 6 USB
 - ![VirtualBox_Win10_06_02_2024_06_11_02](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/5f2cd197-7b5e-42af-81a4-1e23f3e29f7f)
 - This hardware does not originally support the 'SBX Pro Studio Surround' effect. So I'm implemented some effects using hardware processing for effects that were originally supported, and using software processing for effects that were not originally supported. According to the original plan, I was going to implement it so that I could control everything from one control panel as shown below, but the control panel kept malfunctioning and was driving me crazy. So I had no choice but to implement it using the 'THX TruStudio Pro' control panel. So the original effects of using hardware processing can be found in the existing control panel, and the originally unsupported effects of using software processing can be found in the 'THX TruStudio Pro' control panel.

 - ![sb1540_mod](https://github.com/kgtmaven/SoundBlasterUSBAudioMod/assets/24592498/654e51ba-b5e4-4f59-8052-5b6754effadc)



<br/>

## Notes
 - On Sound Blaster X-Fi Notebook, the current driver's 2ch stereo output mode is limited to 16-bit. To use 24-bit mode, switch the output setting to 5.1 channel output mode, or use the https://github.com/kgtmaven/SoundBlasterUSBAudioLegacyMod driver.
 - To use the Sound Blater X-Fi MB2 and THX TruStudio Pro, additional Activation is required. (KGAs something, do it your self.)
 - To use the Dolby Digital Live and DTS Connect, 'Dolby Digital Live & DTS Connect Pack' Software and additional Activation is required. (KGAs something, do it your self.)
 - When installing the driver, you must boot in 'Disable driver signature enforcement' mode.
