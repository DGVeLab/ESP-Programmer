USB Driver Package
This folder contains the official USB-to-UART drivers required for proper communication with ESP8266 and ESP32 development boards.
These drivers are provided unmodified and are redistributed according to the terms set by their respective manufacturers.

📌 Included Drivers
CH34x USB-to-Serial Driver
- Manufacturer: WCH (WinChipHead)
- Official site: https://www.wch-ic.com/
- Purpose: Required for boards using the CH340 / CH341 USB bridge

CH91xx (CH9102 / CH9102F) USB-to-Serial Driver
- Manufacturer: WCH (WinChipHead)
- Official site: https://www.wch-ic.com/
- Purpose: Required for boards using the CH9102 / CH9102F USB bridge (commonly found on newer ESP32 Mini boards)

CP210x USB-to-UART Bridge VCP Driver
- Manufacturer: Silicon Labs
- Official site: https://www.silabs.com
- Purpose: Required for boards using the CP2102 / CP2104 / CP210x USB bridges

📄 Licensing and Redistribution Notice
The drivers included in this package:
- Are property of their respective manufacturers:
-- WCH (CH34x / CH91xx)
-- Silicon Labs (CP210x)
- Are distributed without modifications
- Are included solely for convenience, in order to support users who need USB communication with ESP-family devices
- Must retain all manufacturer-provided files, copyright notes, and licensing information
Users wishing to obtain the most up-to-date versions are encouraged to download them directly from the official websites.

⚠️ Disclaimer
ESP Programmer 2 does not modify, alter, or reverse-engineer these drivers.
They are redistributed exactly as released by their respective vendors.
If you experience installation or compatibility issues, please refer to the official manufacturer documentation.

🔗 Official Download Sources
- WCH CH34x
http://www.wch.cn/downloads/CH341SER_ZIP.html

- WCH CH91xx (CH9102 family)
https://www.wch-ic.com/downloads/CH9102EVT_ZIP.html

- Silicon Labs CP210x
https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers
