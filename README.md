# basicmodem
A fork of basicmodem to work for UK caller ID modems (tested on Zoom Telephonics 3049 V.92 56K External 56K Data/Fax Modem)

A wrapper library for sending commands to USB modems. Features:

 - Writes commands to modem, returns response from modem
 - Enables caller id (via AT+VCID=1) and collects information for incoming calls
 - Provides a callback for incoming call notification
