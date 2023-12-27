# MSI-MODERN-15-A5M

<img src="Screenshot 2023-10-13 at 03.41.29.png">

---

 <a href="https://www.apple.com/macos">
  <img src="https://img.shields.io/badge/Sonoma-14.0-informational.svg">
 </a>
 <a href="https://github.com/acidanthera/OpenCorePkg">
  <img src="https://img.shields.io/badge/OpenCore-0.9.5-informational.svg">
 </a>
 <a href="https://github.com/saeidex/ryzentosh-msi-modern-15-a5m/blob/main/LICENSE">
  <img src="https://img.shields.io/github/license/saeidex/ryzentosh-msi-modern-15-a5m">
 </a>

| **Category**    | **Component**                   | **Final Situation** |
| --------------- | ------------------------------- | :-----------------: |
| **CPU**         | Ryzen 5 5500u                   | :heavy_check_mark:  |
| **Graphics**    | Radeon™ Graphics (512MB) `iGPU` | :heavy_check_mark:  |
| **Drive**       | Kingston NVMe v1.3.0 `SSD`      | :heavy_check_mark:  |
| **Speaker**     | Realtek ALC256                  | :heavy_check_mark:  |
| **Mic**         | Realtek ALC256                  |         :x:         |
| **Headset**     | ComboJack                       | :heavy_check_mark:  |
| **Wireless**    | MediaTek RZ608                  |         :x:         |
| **Card Reader** | Realtek PCI-E Card Reader       | :heavy_check_mark:  |
| **Keyboard**    | Standard PS/2 Keyboard          | :heavy_check_mark:  |
| **Touchpad**    | HID-compliant mouse             | :heavy_check_mark:  |

<!-- ## Pre-Installation: -->

## Post-Installation:

### Fix Headset ComboJack:

Open Terminal and Run:

```bash
cd Desktop
git clone https://github.com/lvs1974/ComboJack.git
bash ComboJack/ComboJack_Installer/install.sh
rm -rf ComboJack
```

Reference: https://github.com/lvs1974/ComboJack

## Facts:

- As you know, WiFi(+BlueTooth) doesn't work and there is no ethernet port on this laptop, that's why `HoRNDIS.kext` for USB tethering is the only blessing for us.
