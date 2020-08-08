### Hackintosh for Asus ROG Strix Z390-E Coffee Lake
###### ❗️08.08.2020 - Updated to latest OpenCore 0.6.0
__Version: OpenCore 0.6.0 MacOS Catalina 10.15.6__ by [OpenCore-Desktop-Guide](https://dortania.github.io/OpenCore-Desktop-Guide/)

### 📸 Screenshots
<details>
<summary>About</summary>

![About](_resources/about.png)

</details>
<details>
<summary>Benchmarks</summary>

![Disk](_resources/disk.png)

![Cinebench](_resources/cinebench.png)

![Geekbench](_resources/geekbench.png)

</details>

### 📃 Hardware
<details>
<summary>🖥 Mac</summary>

* Motherboard: ASUS ROG STRIX Z390-E Gaming ATX (s-1151)
* CPU: Intel Core i5-9600K 3.7GHz/9MB (s-1151)
* GPU: Radeon RX 580 8GB DDR5 Sapphire Pulse
* RAM: Crucial Ballistic Sport LT Red  3200MHz (16x2)
* Memory: Samsung 970 EVO Plus 500GB
* WIFI/Bluetooth: [Fenvi T919](https://www.aliexpress.com/item/32778371977.html)
* Power: 650W Corsair RM650X
* CPU Cooler: Be Quite Dark Rock Pro 4
* Case: DeepCool Matrexx 55
* Monitor: LG UltraFine 27UL650-W 27’’
* Mouse: Logitech MXMaster 2S
* Keyboard: Varmilo VA108MAC

</details>

<details>
<summary>🎮 Windows</summary>

* Kingston SKC400S37 128Gb
* WD Caviar Blue WD10EZEX 1 Tb

</details>

### 🔄 System Status
✅ **What's working?**
- Everything

✳️ **Some details**
* [USB](_usb_map/usb_table.md)
* Bluetooth & Wi-Fi (via [Fenvi T919](https://www.aliexpress.com/item/32778371977.html))
* [NVMe](_resources/m2_info.png)
* Onboard Bluetooth. Try this [kext](https://github.com/zxystd/IntelBluetoothFirmware).

### ❗️Before Usage
1. Update SMBIOS. Follow the simple [guide](https://dortania.github.io/OpenCore-Desktop-Guide/post-install/iservices.html#generate-a-new-serial).
2. Details about [M.2 slots setup](_resources/m2_info.png).

### ⚠️ BIOS
1. Update BIOS to the latest version.

<details>
<summary>2. Follow this settings</summary>

|Option|Flag|
|-|-|
|Fast Boot | disable|
|Secure Boot | disable
|VT-d | disable
|CSM | disable
|CFG-Lock | disable
|Serial Port | disable
|WiFi & Bluetooth | disable
|Above 4G | enable
|XHCI Hand-off | enable
|OS Type | windows |
|XMP II profile (optional)| enable|

</details>

### 😇 Config Sanity
You can check config sanity [here](https://opencore.slowgeek.com/?file=coffeelake060fE9kZE&rs=coffeelake060).

### 🗺 USB Map
Build has a USBMap.kext.\
Check [usb table](_usb_map/usb_table.md) for details.

### 🛠 Tools
<details>
<summary>Must have OpenCore hackintosher's tools</summary>

* [MountEFI](https://github.com/corpnewt/MountEFI) - Helps to mount /EFI folder
* [ProperTree](https://github.com/corpnewt/MountEFI) - A way to open config.plist
* [USBMap](https://github.com/corpnewt/USBMap) - Tool to make a usb map
* [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) - Apple seral generator
* [Lilu-and-Friends](https://github.com/corpnewt/Lilu-and-Friends) - To update kexts
* [OCConfigCompare](https://github.com/corpnewt/OCConfigCompare) - To update OC

</details>

### 📩 Credits
Config by [@lbrdev](https://github.com/lbrdev)
