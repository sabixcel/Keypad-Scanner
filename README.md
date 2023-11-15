# Keypad-Scanner

The keypad scannere is wired in a matrix form with a switch at the intersection of each row and column.
The purpose of the keypad scanner is to determine which has been pressed and ouput a binary number which corresponds to the key number.

This project was made in Vivado HLS environment. It involves creating of an integrated circuit. The block diagram for the FPGA contains:
-a scanner block (it scans the rows and columns of the keypad);
-a keyscan block (it generates the column signals to scan the keypad);
-a standby block (it generates a signal K1 when a key has been pressed and a signal K2 after it has been debounced);
-a decoder (when a valid key is detected, this block determines the key number from the row and column numbers).
