Flashing Instructions
Use the official Espressif web tool:           https://espressif.github.io/esptool-js/
Connect your ESP32 board via USB.
Select the .bin file you received.
Set the flash offset to 0x10000.
Click “Program” to flash the binary.
Open a serial monitor at 115200 baud to interact with MicroFox.

Command List
LS ---->  List all entries in tape RAM.
Cat <filename> → Display contents of a file.
MKDIR <foldername> → Create a new directory entry.
RM <name> → Remove a file or directory.
MKTXT <filename> <content> → Create a new text file with content.
Touch <filename> → Create an empty file.
