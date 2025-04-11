# 🖥️ Hackintosh Build – Ryzen 7 3700X | X570 | RX 6700XT

This is my personal Hackintosh configuration using OpenCore `0.8.8` on an AMD Ryzen system. It's stable, clean, and running macOS smoothly.

![Screenshot](https://github.com/SheikhFoysaldiu/Zen-7-3700x-x570-mb-6700xt/blob/main/Screenshoots/Screenshot%202025-04-11%20at%2012.42.22%E2%80%AFPM.png?raw=true)

---

## 🧰 Specs

| Component     | Model / Version                       |
|---------------|----------------------------------------|
| **Bootloader**| OpenCore `0.8.8`                       |
| **Motherboard** | MSI X570 Tomahawk WiFi Gaming       |
| **CPU**       | AMD Ryzen 7 3700X                      |
| **GPU**       | AMD Radeon RX 6700 XT                 |

---

## ✅ What's Working

| Feature            | Status        |
|--------------------|---------------|
| macOS Boot         | ✅ Yes         |
| GPU Acceleration   | ✅ Yes         |
| Audio              | ✅ Yes (via AppleALC) |
| Ethernet           | ✅ Yes         |
| USB Mapping        | ✅ Properly configured |
| Sleep/Wake         | ✅ Works well  |
| iMessage / FaceTime| ✅ Working with proper config |
| Wi-Fi              | ✅ Works well |

---

## 🧩 Kexts Used

- `Lilu.kext`
- `NootRx.kext`
- `VirtualSMC.kext`
- `AppleALC.kext`
- `USBMap.kext`
- (Add any others you've used)

---

## 📝 Notes

- SMBIOS should be generated individually (do **not** reuse).
- BIOS is tuned for stability – feel free to ask for my settings.
- macOS version used: *14.7.5 (Sonoma)*

---

## 🙌 Credits

Huge thanks to the OpenCore community and Dortania’s guides 🙏

---

