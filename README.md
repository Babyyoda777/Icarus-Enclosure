# Icarus Enclosure

This repo contains the enclosure files for the PCB, designed to be CNC milled at PCBWay.

This project aims to produce a fully assembled Meshtastic node based on the ESP32-S3 and RA-01SH, both of which are avaliable for assembly. The only components to be bought outside are the antenna and LiPo battery. The PCB will include battery charging and SMA connector. I am a student from the UK doing my A Level DT project and this is my custom PCB for that!

Meshtastic® is a project that enables you to use inexpensive LoRa radios as a long range off-grid communication platform in areas without existing or reliable communications infrastructure. This project is 100% community driven and open source!

Meshtastic utilizes LoRa, a long-range radio protocol, which is widely accessible in most regions without the need for additional licenses or certifications, unlike HAM radio operations.
These radios are designed to rebroadcast messages they receive, forming a mesh network. This setup ensures that every group member, including those at the furthest distance, can receive messages.
Additionally, Meshtastic radios can be paired with a single phone, allowing friends and family to send messages directly to your specific radio. It's important to note that each device is capable of supporting a connection from only one user at a time.

This is a rough 3D print but I plan for it to be CNCed out of polycarb eventually! Estimated cost per piece is $90 according to PCBWay audit and I need four of them so around $360 (very expensive)


Board Features:
- ESP32-S3 N8R8 MCU (Bluetooth and Wi-Fi)
- MCP78731 Battery Charging and Load sharing
- BME280 Environment sensor (temperature, humidity and barometric pressure)
- RA-01SH LoRa module with SMA connector and 868mHz antenna
- SSD106 1.3" OLED
- Up, Down and Select buttons + BOOT and RESET
- DW01A Battery protection 
- USB-C
- Additional exposed GPIO for expansion e.g. GPS module.

# Sponsor
This project is sponsored by PCBWay, checkout their great PCB and PCBA as well as CNC here: https://pcbway.com/g/CzERmm

![PNG image](https://github.com/user-attachments/assets/3042b4ad-df3d-4577-ba26-5d70e5f4352c)

![IMG_0119](https://github.com/user-attachments/assets/c61de444-5e6b-497b-b0a5-52c3598c2bd0)

![IMG_0118](https://github.com/user-attachments/assets/c5277f37-d323-43b1-b5fe-04353c503286)

![IMG_0121](https://github.com/user-attachments/assets/8ff2fd38-35b0-48f5-b0a9-5804a612b006)

![IMG_3464](https://github.com/user-attachments/assets/746ff8d6-4637-480a-8ccf-224b93c6cb8a)

![IMG_3465](https://github.com/user-attachments/assets/c2fe237f-0c0a-475c-9f37-a34d05f37ebc)


