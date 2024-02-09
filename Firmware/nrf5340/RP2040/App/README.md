## Setup

**Light Sensor Integration with RP2040 and BT40 Boards**

### Programming RP2040

1. Download the UF2 file from RP2040/App/binaries.

2. Program the RP2040 board using the UF2 file. Ensure PIN2 of RP2040 is connected to LED1_P11 of the Light Sensor Circuit Board, PIN4 is connected to LED2_P13, and GND is connected to GND.

3. Ensure PIN 1 (RX) of RP2040 is connected to the corresponding TX pin on the BT40 board, PIN 0 (TX) is connected to the corresponding RX pin on the BT40 board.