# OpenCore 0.8.8 - Lenovo Ideapad 15IML05 i5 10210U (No dGPU)
My EFI for the Lenovo Ideapad 15IML05 (No dedicated graphics)
<br>
<p align="center">
<img src="https://raw.githubusercontent.com/MatteoBax/lenovo-ideapad-15IML05-hackintosh/main/.images/Screenshot%202023-02-11%20at%2016.13.01.png"></img> 
</p>
<br>
## Specs

| Component      | Brand                                     |
|----------------|-------------------------------------------|
| **CPU**        | `Intel Core i5-10210U @ 1.6 GHz`           |
| **iGPU**       | `Intel UHD Graphics`                  |
| **dGPU**       | `NVIDIA GeForce MX 130`                  |
| **Storage**    | `SAMSUNG MZALQ256HBJD-00BL2`  |
| **Audio Codec** | `ALC 230`                |
| **OS**         | `macOS Ventura 13.2 (22D49)`            |

## Working/Not Working

<details>
<summary>iGPU</summary>

- [x] Intel UHD iGPU - Backlight support
- [x] Intel UHD iGPU - HDMI Output
- [x] Intel UHD iGPU - H264 & HEVC
</details>

<details>
<summary>dGPU</summary>

- [ ] NVIDIA GeForce MX 130
</details>

<details>
<summary>Audio</summary>

- [x] Internal Speakers
- [x] Internal Microphone
</details>

<details>
<summary>USB</summary>
  
- [x] All USB ports working and mapped
- [x] SD Card Reader
- [x] Internal Webcam
</details>

<details>
<summary>Keyboard</summary>
  
- [x] Keyboard (PS2 based)
</details>

<details>
<summary>Trackpad</summary>
  
- [x] I2C Touchpad with gestures (Thanks to [**lshbluesky**](https://github.com/lshbluesky))
</details>

<details>
<summary>Misc</summary>
  
- [ ] Sleep/Wake not working, straight up disable Sleep Mode (read [**Bildcraft1's SleepFix.md**](https://github.com/Bildcraft1/lenovo-ideapad-15ibd-hackintosh/blob/main/SleepFix.md)
- [x] Sensors CPU, iGPU, Battery, NVMe, Fans
- [x] Native NVRAM support
- [x] Recovery (macOS) boot from OpenCore
</details>

## Credits

* **Apple** for macOS
* [**Acidanthera**](https://github.com/acidanthera) for OpenCore and the majority of the kexts
* [**RehabMan**](https://github.com/RehabMan) for contributing to most of the ACPI patching guides I used
* [**Feartech**](https://www.tonymacx86.com/members/feartech.877703/) for fixing boot issue
* [**lshbluesky**](https://github.com/lshbluesky) for fixing I2C Touchpad issue
* [**aben**](https://www.insanelymac.com/forum/profile/2480073-aben/) for fixing black screen issue on lock screen
