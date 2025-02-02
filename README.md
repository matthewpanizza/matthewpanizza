# Hey there, I'm Matthew Panizza 👋
**An Embedded Software Engineer with a passion for automotive electronics**

I enjoy brainstorming new ways of using microcontollers and automating things in my life. I then like to take that idea and develop something all the way from a rough sketch to a fully-functional prototype with user interfaces, 3D printers, and sometimes mobile apps. Reverse-engineering is also a lot of fun - I've reverse-engineered electric skateboard batteries, car instrument clusters and a host of other electronics.

|  <div style="width:50px">                                                                                                        | <div style="width:200px">Languages I've Used</div> | <div style="width:50px"></div>                                                                                                        | <div style="width:200px">Tools I've Used</div> |   
| :------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------- | :-----------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------- |  
| <img height="30" src="https://user-images.githubusercontent.com/25181517/192106073-90fffafe-3562-4ff9-a37e-c77a2da0ff58.png">    | **C++**                                            | <img height="30" src="https://www.particle.io/android-chrome-512x512.png">                                                            | **Particle Microcontrollers**                  | 
| <img height="30" src="https://user-images.githubusercontent.com/25181517/192106070-46255bcf-65e6-4c6b-a296-bf8d0d8fb2a7.png">    | **C**                                              | <img height="30" src="https://github.com/marwin1991/profile-technology-icons/assets/136815194/a57a85ba-e2dd-4036-85b6-7e1532391627">  | **Arduino Microcontrollers**                   | 
| <img height="30" src="https://user-images.githubusercontent.com/25181517/183423507-c056a6f9-1ba8-4312-a350-19bcbc5a8697.png">    | **Python**                                         | <img height="30" src="https://github.com/user-attachments/assets/9f931c45-0585-4db0-86a7-25ce3f5bef25">                               | **PyCharm**                                    |
| <img height="30" src="https://user-images.githubusercontent.com/25181517/121405384-444d7300-c95d-11eb-959f-913020d3bf90.png">    | **C#**                                             | <img height="30" src="https://user-images.githubusercontent.com/25181517/192108891-d86b6220-e232-423a-bf5f-90903e6887c3.png">         | **Visual Studio Code**                         |
| <img height="30" src="https://user-images.githubusercontent.com/25181517/121406389-6267a300-c95e-11eb-8d67-f1e22afe8aea.png">    | **Swift**                                          | <img height="30" src="https://user-images.githubusercontent.com/25181517/186711578-bf30cb30-40b7-4b45-95a5-bdf837c372e7.png">         | **Xcode**                                      |


## Projects to Check Out
### [Decentralized Low Voltage System](https://github.com/matthewpanizza/DecentralizedLV-Boards)
A system of embedded microcontrollers that relays electrical information from the driver to accessory components over CAN Bus. Replaces large accessory wiring harnesses with a four wire (two power + two CAN) system.
- [DecentralizedLV-Boards](https://github.com/matthewpanizza/DecentralizedLV-Boards) - Submodule used as an API for inter-board communication and a platform-agnostic CAN controller.
- [DecentralizedLV-DashController](https://github.com/matthewpanizza/DecentralizedLV-DashController) - Board which takes input from the driver and controls lights, drive mode, and instrument cluster.
- [DecentralizedLV-LPDRV](https://github.com/matthewpanizza/DecentralizedLV-LPDRV) - Low Power Driver board which drives lights, pumps, and other accessories based on CAN data.
- [DecentralizedLV-ULPDRV](https://github.com/matthewpanizza/DecentralizedLV-ULPDRV) - Ultra Low Power Driver board, a miniature LPDRV with pin passthroughs for SPI and UART peripherals.
- [DecentralizedLV-HVController](https://github.com/matthewpanizza/DecentralizedLV-HVController) - High Voltage Controller board which handles the battery management system and motor inverter.
- [DecentralizedLV-Sense](https://github.com/matthewpanizza/DecentralizedLV-Sense) - Sensor board. A legacy version of the Dashboard Controller with slightly less functionality.

<img height="200" src="Pictures/AssembledPCBs.jpg">

### [Boosted Unbrick Firmware](https://github.com/matthewpanizza/BoostedUnbrickFirmware)
Custom firmware for a Microchip dsPIC33 to interface with all components on the PCB of a Boosted Extended Range Battery (XRB). This custom firmware helped me restore functionality to a XRB which had a software lockout after the Li-ion cells became imbalanced.

<img height="200" src="https://github.com/matthewpanizza/BoostedUnbrickFirmware/raw/main/Pictures/Desoldered.jpg">

### [CAN Bus Analyzer](https://github.com/matthewpanizza/CANAnalyzer)
A tool for analyzing received CAN Bus frames and emulating CAN Bus messages. Complex loops over different combinations of addresses and data bytes can be done using a serial console. This tool was used to determine the CAN Bus messaging system used for a 2018 Toyota Camry Instrument Cluster which is included in the [DecentralizedLV-Boards API](https://github.com/matthewpanizza/DecentralizedLV-Boards) and controlled by the [DecentralizedLV-DashController](https://github.com/matthewpanizza/DecentralizedLV-DashController) board.

<img height="200" src="https://github.com/matthewpanizza/CANAnalyzer/raw/main/Pictures/ClusterError.jpg">

### [SkateInfoView](https://github.com/matthewpanizza/SkateInfoView)
An iOS app paired with a Bluetooth Low Energy (BLE) microcontroller which monitors power usage on an electric skateboard. The microcontroller reads voltage, current, speed and other parameters and relays them over BLE to a companion app on an iPhone. There is also an Apple Watch companion app which received relayed information from the iPhone.

<img height="150" src="Pictures/SkateInfoView.jpg">
