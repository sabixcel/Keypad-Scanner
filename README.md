# Keypad-Scanner

The keyboard scanner is wired in a matrix form, with a switch at the intersection of each row and column.
The purpose of the keyboard scanner is to determine which one was pressed and output a binary number that corresponds to the number of the key.

This project was done in the Vivado HLS environment. This involves creating an integrated circuit. The block diagram for the FPGA contains:
-a scanner block (scans the rows and columns of the keyboard);
-a keyscan block (generates the column signals to scan the keyboard);
-a standby block (generates a K1 signal when a key has been pressed and a K2 signal after it has been canceled);
-a decoder (when a valid key is detected, this block determines the key number from the row and column numbers).
