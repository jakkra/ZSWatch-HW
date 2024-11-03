# CHANGELOG

## [2.0.6]

**Fixed:**

**Added:**

- Add new vibration motor

**Changed:**

- Move DISPLAY-CLK from P0.08 to P0.09
- Move DISPLAY-DATA from P0.09 to P0.08
- Move all components into a local KiCad library

**Removed:**

## [2.0.5] - 29.07.2024

**Fixed:**

- Wrong address for BMP581 in documentation
- Fix non ideal footprint for NTS0104GU12

**Added:**

- Add nPM1300 as power management solution
- Add QR code with projects GitHub URL
- Add solder bridge for current measuring
- Add I2S microphone
- Add buzzer
- Add USB support
- Add marker for display cable orientation
- Add markers for better IC placements
- Add PCB cutout for BME688 sensor
- Add MX25L51245GZ2I Flash memory
- Add RV-8263-C8 RTC

**Changed:**

- Change value for ISET resistor from 10k to 12k
- Move BTN_2 from P0.30 to P1.10
- Move BTN_3 from P1.12 to P0.31
- Move DRV_VIB_EN from P1.14 to P1.05
- Move BMI270_IN1 from P0.21 to P1.08
- Move BMI270_IN2 from P0.19 to P1.04
- Move DRV_VIB_PWM from P1.15 to P1.05
- Move DRV_VIB_EN from P1.05 to P1.15
- Move BTN_4 from P1.06 to P0.26
- Replace ESDALC6V1W5 with ESDALC6V1P5

**Removed:**

- Remove GPIO pads
- Remove BMP581 INT
- Remove copper under BME688 sensor

## [2.0.4] - 29.10.2023

**Added:**

- Add revision variable for PCB revision in copper

**Changed:**

- Move DISPLAY_CS from P0.11 to P0.12
- Move DISPLAY_DC from P0.12 to P0.11
- Move DISPLAY_EN from P0.15 to P1.01
- Move SENSOR_SCL from P0.18 to P0.07
- Move SENSOR_SDA from P0.17 to P0.10
- Move INT2_LIS from P0.14 to P0.19
- Move Flash to to dedicated QSPI pins on nRF5340

## [2.0.3] - 25.09.2023

**Added:**

- Add light sensor
- Add GPIO pads

**Changed:**

- Move DISPLAY_EN from C4 (P1.01) to D1 (P0.15)
- Move INT1_LIS from D3 (P0.03) to E3 (P0.21)
- Move INT2_LIS from E3 (P0.21) to E2 (P0.14)
- Move DRIV_VIB_EN from E9 (P1.05) to F8 (P1.14)
- Move DISPLAY_RST from D7 (P0.23) to C5 (P0.02)
- Move BTN_2 from J9 (P0.31) to H9 (P1.11)
- Move BTN_3 from H9 (P1.11) to H8 (P0.30)
- Move CHG from H8 (P0.30) to G9 (P1.13)
- Remove pin header as dock connector with magnetic contact

**Removed:**

- Remove heart rate sensor
