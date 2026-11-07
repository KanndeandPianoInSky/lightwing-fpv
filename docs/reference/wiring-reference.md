# Aocoda-RC F4 V1.1 Wiring Reference

The original reference shows the F4 V1.1 board. The build list specifies an Aocoda-RC F405 V2. Verify the pin labels and connector order on your board and ESC before applying power.

| Device | Connections shown on the F4 V1.1 reference |
| --- | --- |
| Four-in-one ESC | S1 through S4 for motor signals, R3 for telemetry, CUR for current sense, GND and VBAT. Match the harness wire order to the ESC pinout. |
| Analog camera | Video to CAM, ground to G and camera power to the appropriate supply. |
| Analog video transmitter | Video input from VTX, ground to G and control to T4. Check the transmitter input voltage before choosing a supply pad. |
| Addressable LED strip | LED data to LED, ground to G and power to 5V. |
| PPM or iBUS receiver | Power to 4V5, ground to G and signal to R2. |
| SBUS receiver | Power to 4V5, ground to G and signal to SBUS. |
| CRSF or ELRS receiver | Receiver TX to R2, receiver RX to T2, ground to G and power to 4V5. |
| GPS | GPS TX to R1 and GPS RX to T1. Connect SDA and SCL to their matching pads if used. |
| Buzzer | Positive lead to 5V and negative lead to BZ. |
| DJI air unit | The diagram shows 9V power, ground, T4 to RX, R4 to TX and SBUS to SBUS. Verify the air unit pinout for your model. |

The reference assigns UART1 to GPS, UART2 to the receiver and UART4 to the video transmitter. UART3 and UART5 are user-configurable.
