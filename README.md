# Flight-Controller-FC-R1

A Flight Controller, made for rockets, atmospheric data logging and servo control.

## What can it do

- Gyro and Accelerometer: Reads 6 axis motion tracking data using the ICM-45686 IMU.
- Altitude Tracking: Measures barometric pressure and altitude changes with the onboard BMP580 sensor.
- Processing Power: Driven by a STM32F722RETx6.
- 2 Servo Outputs: Dedicated PWM headers to control deployment mechanisms, recovery hatches, or TVC systems.
- Storage: Integrated MicroSD card slot for flight data logging.
- Power Management: Onboard LiPo battery charger circuit combined with a 3.3V Buck regulators for stable voltage delivery.
- Flashing: Hardware BOOT and RESET buttons for code flashing.

## Why does it exist

I really wanted to do something aero hence i havent done anything for it in a while and when i saw the guide for a flightcontroller made for rockets it was just a knight in shining armor.

Learned rotated PCB layout and Zone power delivery in KiCAD.

## BOM

| Component | Function | LCSC number |
| :--- | :--- | :--- |
| STM32F722RET6 | Main Microcontroller | - |
| ICM-45686 | Gyro + Accelorometer | C22459454 |
| BMP580 | High-Accuracy Barometric Pressure Sensor | C22391138 |
| MicroSD Slot | Storage | C91145 |
| TPS63070RNMR |  5V Buck Regulator | C109322 |
| 3.3V Buck Regulator | Voltage Regulator | - |
| BQ25883RGER | Battery Charger  | C544362 |
| USB-C Receptacle | USB-C 16 Pin | C2765186 |

## Tools

- PCB Design: KiCAD
- Reference Guide: Based on a Flightcontroller guide by NotARoomba

## Schematic

<img width="983" height="680" alt="image" src="https://github.com/user-attachments/assets/e367f9ad-5d39-4150-9d97-ca80045a1b8e" />

## PCB

<img width="647" height="579" alt="image" src="https://github.com/user-attachments/assets/084f9f09-4e3e-4958-98c8-f6d83fc6f673" />

<img width="612" height="575" alt="image" src="https://github.com/user-attachments/assets/a0f84569-16c8-4650-b9b8-bd21db2388aa" />

## Extra

Credits:
- NotARoomba (Guide)
- Omocat (Silkscreen pixelarts only on my PCB not in the files)

## Bonus

Nothing this time around.
