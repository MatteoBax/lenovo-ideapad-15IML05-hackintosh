# OpenCore 0.8.8 - Lenovo Ideapad 15IML05 i5 10210U (No dGPU)
My EFI for the Lenovo Ideapad 15IML05 (No dedicated graphics)
<br>
![macOS](https://raw.githubusercontent.com/MatteoBax/lenovo-ideapad-15IML05-hackintosh/main/.images/Screenshot%202023-02-11%20at%2016.13.01.png)

## Specs

| Component      | Brand                                     |
|----------------|-------------------------------------------|
| **CPU**        | `Intel Core i5-10210U @ 1.6 GHz`           |
| **iGPU**       | `Intel UHD Graphics`                  |
| **Storage**    | `SAMSUNG MZALQ256HBJD-00BL2`  |
| **Audio Code** | `ALC 230`                |
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
  
<!--- [ ] Sleep/Wake not working, straight up disable Sleep Mode (read SleepFix.md)-->
- [x] Sensors CPU, iGPU, Battery, NVMe, Fans
- [x] Native NVRAM support
- [x] Recovery (macOS) boot from OpenCore
</details>
