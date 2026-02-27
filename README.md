# SHARKY 

DISCLAIMER: This project is for educational and security research purposes only. The user is solely responsible for compliance with local laws regarding radio interference, and the author assumes no liability for any misuse or legal consequences arising from this hardware.

This project is the most hacky vibes kinda I saw this in my youtube recommendation, its a 2.4ghz wifi and bluetooth jammer/deauther. It uses a esp32 and two nRF24L01+PA+LNA which makes it crazy at max power.

# NOTE !!! 🟥🟥🟥

**For the 2nd reviewer pls note since the lipo battery is out of stock from the website , and i couldn't find anywhere else online , I am going to buy it locally , so it might differ with the requested funding ammount pls ping on slack for any confusion**


# FLASHING INSTRUCTIONS

- You need to cloen this repo, open the folder in the IDE.
- PlatformIO will automatically detect the platformio.ini and download the RF24 library.
- Connect your ESP32 and click the upload button in the bottom status bar.
- After you are good to go, it will start working!!

# SHOWCASE

<img width="1048" height="769" alt="Screenshot 2026-01-24 195544" src="https://github.com/user-attachments/assets/7602787e-b11b-4d2c-a386-ed132fd28536" />
<img width="859" height="679" alt="Screenshot 2026-01-24 193912" src="https://github.com/user-attachments/assets/99c46c13-6165-4c17-84ca-e122665a4263" />
<img width="933" height="776" alt="Screenshot 2026-01-24 194104" src="https://github.com/user-attachments/assets/c6eb734c-fac1-4ae8-8436-7dd8e6a680c8" />

# PCB 

<img width="1379" height="861" alt="image" src="https://github.com/user-attachments/assets/3665e12b-1664-431f-b477-6968334928d4" />
<img width="1082" height="605" alt="image" src="https://github.com/user-attachments/assets/b850473a-5009-4a0c-8079-daf965db7b56" />


# SEEEDSTUDIO CART 

<img width="1797" height="700" alt="image" src="https://github.com/user-attachments/assets/4dc7d8d2-538c-4b00-a232-2f071e0a6fba" />
<img width="1241" height="733" alt="image" src="https://github.com/user-attachments/assets/74e738c9-ef36-45cd-bfa3-41efd4657a64" />
<img width="1641" height="845" alt="Screenshot 2026-01-22 235432" src="https://github.com/user-attachments/assets/f668d26c-0257-47b1-ba6b-26d54bce5b33" />

# QUARTZCOMPONENTS CART 

<img width="470" height="668" alt="image" src="https://github.com/user-attachments/assets/b5da9255-fb47-417e-b1c8-635502f53d60" />
<img width="489" height="675" alt="image" src="https://github.com/user-attachments/assets/c615ae6e-2527-40db-b5c6-f2ebc0243cce" />


# BOM 

| Name | Qty | Price (INR) | Vendor | Link |
|------|-----|--------------|--------|------|
| TP4056 Module | 1 | 16 | QuartzComponents | [Link](https://quartzcomponents.com/products/tp4056-battery-charging-protection-module-type-c) |
| NRF24L01+PA+LNA | 2 | 276 | QuartzComponents | [Link](https://quartzcomponents.com/products/nrf24l01-pa-lna-wireless-2-4ghz-rf-transceiver-module-with-sma-antenna) |
| ESP32-DEVKITV1 | 1 | 345 | QuartzComponents | [Link](https://quartzcomponents.com/products/esp32-30-pin-development-board-with-wi-fi-and-bluetooth) |
| JST-XH 2.54mm 2P Connector | 1 | 3 | QuartzComponents | [Link](https://quartzcomponents.com/products/2-pin-jst-male-2-54-pitch) |
| 100uF Electrolytic Capacitor | 2 | 6 | QuartzComponents | [Link](https://quartzcomponents.com/products/100uf-25v-radial-electrolytic-capacitor) |
| SPDT Slide Switch | 1 | 6 | QuartzComponents | [Link](https://quartzcomponents.com/products/dpdt-miniature-slide-switch) |
| 3.7V 1200mAh Li-Po Battery | 1 | 228 | Local Shop | Local Shop |
| M3 6mm Screw | 1 | 5 | QuartzComponents | [Link](https://quartzcomponents.com/products/phillips-head-m3-6mm-bolt-mounting-screw-for-pcb) |
| M3 12mm Screw | 1 | 8 | QuartzComponents | [Link](https://quartzcomponents.com/collections/all/products/phillips-head-m3-12mm-bolt-mounting-screw-for-pcb-pack-of-4) |
