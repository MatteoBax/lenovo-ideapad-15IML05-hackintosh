# OpenCore 0.9.4 - Lenovo Ideapad 15IML05 i5 10210U (No dGPU)
My EFI for the Lenovo Ideapad 15IML05 (No dedicated graphics)
<br>
<p align="center">
    <img src=".images/Ventura.png" alt="Ventura">
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
| **OS**         | `macOS Ventura 13.4 (22F66)`            |

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
<summary>Fingerprint reader</summary>
  
- [ ] Fingerprint reader
</details>

<details>
<summary>Trackpad</summary>
  
- [x] I2C Touchpad with gestures (Thanks to [**lshbluesky**](https://github.com/lshbluesky))
</details>

<details>
<summary>Misc</summary>
  
- [ ] Sleep/Wake not working, straight up disable Sleep Mode (read [**Bildcraft1's SleepFix.md**](https://github.com/Bildcraft1/lenovo-ideapad-15ibd-hackintosh/blob/main/SleepFix.md))
- [x] Sensors CPU, iGPU, Battery, Fans
- [ ] The integrated NVMe SSD works but overheats quickly due to TRIM failure. It is advisable to replace the SSD with a supported one (For the list of unsupported SSD see: https://dortania.github.io/Anti-Hackintosh-Buyers-Guide/Storage.html)
- [x] Native NVRAM support
- [x] Recovery (macOS) boot from OpenCore
</details>

## Credits

* **Apple** for macOS
* [**Acidanthera**](https://github.com/acidanthera) for OpenCore and the majority of the kexts
* [**RehabMan**](https://github.com/RehabMan) for contributing to most of the ACPI patching guides I used
* [**Feartech**](https://www.tonymacx86.com/members/feartech.877703/) for fixing boot issue
* [**lshbluesky**](https://github.com/lshbluesky) for fixing I2C Touchpad issue
* [**aben**](https://www.insanelymac.com/forum/profile/2480073-aben/) for fixing black screen issue on lock screen and turbo boost issue
* [**Bildcraft1**](https://github.com/Bildcraft1) for fixing sleep issue
