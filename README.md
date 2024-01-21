This program reads a "hardcopy" screenshot from the Tektronix TDS 224
oscilloscope and saves it to a file.

Configure the oscilloscope:

*  "UTILITY" / "Options" / "Hard Copy Setup":
    * Format: BMP
    * Port: RS232
* "UTILITY" / "Options" / "RS232 Setup":
    * Baud: 19200
    * Flow control: Hard flagging (i.e. RTS/CTS)
    * EOL string: LF
    * Parity: Odd

Connect the scope's RS-232 port to a computer (I use a USB-to-RS232
adapter).

Set the DEV variable.

Run this program, then hit the "HARDCOPY" button on the scope.

It takes about 2-3 minutes to save a screenshot.
