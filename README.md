# AgriRover
## it is a agriculture helping rover that can roam freely and autonoumously to map out the farmland's nutrient map.
Till now we have completed the Actuator Board, Radio Board and the carrier board of the PCB side. and Auger arm, Camera Head,Wheel, Wheel adaptor and LiDar on the CAD side.
this is our done project till now:
Werent able to push development in CAD this week much as abhinav was sick.
Here you can watch all the info of the PCB 

## Motor/Actuator Board:
It is the board responsible for the communication with all the actuators & motor in the rover, it features:
- An onboard programmable STM32G431R6Tx to control everything
- A CAN transceiver SN65HVD230 to add the ability of communicating to the STM32
- 5 (upto 3A) motor output, i m using them to control FIT0522 from DFrobot
- 6 headers [ 6V, SIGNAL, GND ] capable of 3A each servo headers, im using MG996R tho
### Schematic:
<img width="3300" height="2550" alt="schematic-images-0 (3)" src="https://github.com/user-attachments/assets/c57c9cb8-e878-447c-9b3f-90a5f1b1fea2" />
<img width="3300" height="2550" alt="schematic-images-1 (3)" src="https://github.com/user-attachments/assets/bb3749e8-4f9e-4dd0-b214-f68d41d47add" />
### PCB:
<img width="1308" height="688" alt="image" src="https://github.com/user-attachments/assets/9c0de25e-0cf9-4be2-9aa3-f29a6a0611d7" />
<img width="1294" height="688" alt="image" src="https://github.com/user-attachments/assets/eab7e3c0-d55e-4003-b98a-c9a62f19f5aa" />
<img width="1289" height="678" alt="image" src="https://github.com/user-attachments/assets/d76e1fd5-2b81-40d7-8870-8ad17f2514d5" />
<img width="1291" height="681" alt="image" src="https://github.com/user-attachments/assets/019f5eb6-bac6-428b-a0d1-8329542ba4b2" />
<img width="1331" height="828" alt="image" src="https://github.com/user-attachments/assets/84d443a9-c277-467c-a4d8-83e7c4e9cadb" />

## Main Board:
It is the board with a CM4 onboard to perform all the CV things, calculations, handle LiDar, camera etc. it features:
- CM4 multi pin connector
- CAN transceiver, MCP2515-xST with SN65HVD230
- a 22 pin camera header
- a fan controller
- a USB, HDMI, and Ethernet for debugging.
- LiDar Header
- SD card
- Onboard IMU ISM330DHCX
### Schematic:
<img width="4961" height="3509" alt="schematic (2)" src="https://github.com/user-attachments/assets/11903717-4adc-4810-81a0-b6c154a238c9" />
### PCB:
<img width="960" height="858" alt="image" src="https://github.com/user-attachments/assets/da586095-91b4-4357-ae2d-da26031c9184" />
<img width="973" height="849" alt="image" src="https://github.com/user-attachments/assets/ee0e2ffe-3e24-45cd-974c-baa749b0c2cc" />
<img width="942" height="868" alt="image" src="https://github.com/user-attachments/assets/2d75908f-8714-4ff0-846f-add8db810c0d" />
<img width="966" height="843" alt="image" src="https://github.com/user-attachments/assets/e2589c97-21be-40a8-80c8-0a39419237d8" />
<img width="1006" height="834" alt="image" src="https://github.com/user-attachments/assets/64ccdc82-6521-46f8-8e1e-f17ebcfebeed" />
<img width="1026" height="837" alt="image" src="https://github.com/user-attachments/assets/21a2c8ea-edc8-455b-a9a1-e2e0b4e9f430" />
<img width="1451" height="894" alt="image" src="https://github.com/user-attachments/assets/50be7bbb-7eb1-4942-9052-6418bbbbc152" />


## Radio Board
it is the board responsible for communication with the transmitter and the HTTPS through LTE, it features:
- A 40 pin rpi connector, so you can plug it in any rpi
- a SIM7080G with GNSS and RF antenna sma connectors
- a E22-900M22S with SMA connector and UFL both, so whatever u choose
### Schematic:
<img width="3509" height="2481" alt="schematic (3)" src="https://github.com/user-attachments/assets/cba3f874-baec-4f0a-8719-e4689cf7caa4" />
### PCB:
<img width="1015" height="900" alt="image" src="https://github.com/user-attachments/assets/03fe89bf-0b60-4199-a42c-b8b38284231a" />
<img width="1107" height="901" alt="image" src="https://github.com/user-attachments/assets/d6eede59-9dba-4a44-bbe3-1681db25d11a" />
<img width="994" height="919" alt="image" src="https://github.com/user-attachments/assets/2ccfbfac-4709-442a-bf7a-dc9f49968919" />
<img width="992" height="870" alt="image" src="https://github.com/user-attachments/assets/294c3270-0289-4cb2-bcef-476d8e86372d" />
<img width="1246" height="843" alt="image" src="https://github.com/user-attachments/assets/19ff6ac8-39e0-4518-a36b-a1484dc91ea5" />
<img width="1130" height="690" alt="image" src="https://github.com/user-attachments/assets/b594f59f-0301-4415-8010-940bdf553b91" />


## Camera Head:
<img width="515" height="455" alt="image" src="https://github.com/user-attachments/assets/972cbfd1-2e7b-4a86-8f9d-78792f8f53eb" />

## Auger arm:
<img width="955" height="668" alt="image" src="https://github.com/user-attachments/assets/ab138d2a-7213-44df-9491-f11522ebe437" />

## Wheels:
<img width="736" height="648" alt="image" src="https://github.com/user-attachments/assets/51eb0d36-b385-4750-a597-8049cd7b6b9d" />
<img width="1005" height="736" alt="image" src="https://github.com/user-attachments/assets/8a456968-0094-48c8-8548-dab236d5b8d7" />
<img width="1146" height="685" alt="image" src="https://github.com/user-attachments/assets/b8da2e6e-5f80-4e95-85c0-f2ff190a5841" />
<img width="1028" height="726" alt="image" src="https://github.com/user-attachments/assets/6b0ecf0a-e1ac-4d23-be65-2007aa8f8b4f" />


# Journals:
you can read the journals of respective collaborators in the root of this repo as [NAME]-JOURNAL.md
# Roadmap:
- [x] Complete the CM4 Carrier Board by Next week
- [ ] Complete the Chasis till Next week
- [x] fix all the DRC error by this time in the main carrier board
- [ ] make the Power Board 💀 (30A+)
- [x] make the communication board
- [ ] assemble all the individual components in the CAD
[ Abhinav left as he was sick for this week, altho would work on the project tho in future ig ]
