# Hubbly
a USB Hub that extends one Type C port to 4 Type C ports with LEDs indicating which port is on. I made this project because my laptop has only one Type-C port, and I face many problems connecting multiple devices to My Pc.

## Features
* Extend up to 4 ports
* LEDs indicate which port is connected
* Cool images on PCB
## Schematic
I used EasyEDA to wire everything in the schematic. wired some LEDs to each port.
<img width="1012" height="652" alt="Screenshot 2026-05-22 171849" src="https://github.com/user-attachments/assets/080c64d0-52ff-4ce8-9e62-1473cbda3568" />
## PCB 
I routed each component on the PCB.
<img width="1004" height="625" alt="Screenshot 2026-05-24 154216" src="https://github.com/user-attachments/assets/aeacd6bd-5c20-47b1-b65a-58a2528c09a7" />
<img width="1009" height="625" alt="Screenshot 2026-05-24 154237" src="https://github.com/user-attachments/assets/f53d908a-5821-4d17-aa81-3927aae8011a" />
## 3D Model 
<img width="614" height="619" alt="Screenshot 2026-05-29 161525" src="https://github.com/user-attachments/assets/9b9d1fec-8c4f-413a-b7a5-468950df8b85" />
<img width="945" height="596" alt="Screenshot 2026-05-29 161444" src="https://github.com/user-attachments/assets/3d351bd5-0c85-455e-b3ef-8ff512a58031" />

## BOM
| Item                | Reference Designators                                      | Price (USD) | Description                         | Link |
|---------------------|------------------------------------------------------------|-------------|-------------------------------------|------|
| 1uF                 | C1, C2, C3, C4, C5, C7, C8, C12                           |             | Capacitors in the PCB               | https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC---SMD-SMT_Samsung-Electro-Mechanics-CL10A105KB8NNNC_C15849.html |
| 100nF               | C6, C9, C13                                               |             | Capacitors in the PCB               | https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC---SMD-SMT_YAGEO-CC0603KRX7R9BB104_C14663.html |
| 5.1K                | R1, R2, R3, R4, R5, R6, R7, R8, R9, R10                  |             | Resistors in the PCB                | http://lcsc.com/product-detail/Chip-Resistor---Surface-Mount_UNI-ROYAL-0603WAF5101T5E_C23186.html |
| 140K                | R11, R12, R14                                             |             | Resistors in the PCB                | https://www.lcsc.com/product-detail/Chip-Resistor---Surface-Mount_YAGEO-RC0603FR-07140KL_C185372.html |
| 10K                 | R13, R15                                                   |             | Resistors in the PCB                | https://www.lcsc.com/product-detail/Chip-Resistor---Surface-Mount_UNI-ROYAL-0603WAF1002T5E_C25804.html |
| SL2.1s              | U1                                                         |             | USB HUB Controller Chip             | https://www.lcsc.com/product-detail/USB-HUB-Controllers_CoreChips-SL2-1s_C2684433.html |
| TYPE-C16PIN2MD(073)| USB1_DOWNSTREAM, USB2_DOWNSTREAM, USB3_DOWNSTREAM, USB4_DOWNSTREAM, USB_UPSTREAM |             | USB Type-C Connectors               | https://www.lcsc.com/product-detail/USB-Connectors_SHOU-HAN-TYPE-C-16PIN-2MD-073-_C2765186.html |
| JLCPCB              | PCB                                                        | 24.70       | PCB printing                        | N/A |
| BLUE, GREEN, RED, WHITE, YELLOW (5 leds) | LEDS                                | 0.10        | 3mm LEDs                            | https://mostelectronic.com/shop/displays-lcd-7-seg-led/leds-displays-lcd-7-seg-led/led-green-color-3mm/ |
| printify3d          | Enclosure                                                  | 19.15       | 3D printing                         | N/A |
<img width="321" height="313" alt="image" src="https://github.com/user-attachments/assets/cb2acea7-ca7d-4de5-8e3c-d0010c9278a6" />
<img width="1869" height="639" alt="Screenshot 2026-05-29 181718" src="https://github.com/user-attachments/assets/c83f15f2-b8df-43ca-a0f6-139c9d79a9b9" />

## KINE
<img width="496" height="706" alt="Screenshot 2026-05-29 212251" src="https://github.com/user-attachments/assets/3965ccb9-0be3-4b1a-bb0e-5481114984f4" />

