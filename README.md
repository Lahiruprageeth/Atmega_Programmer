# Atmega_Programmer

A tool for programming ATmega328P ICs using **AVRDUDE** and **Java**.
<div style="text-align: center;" >
    <img src="https://github.com/user-attachments/assets/be7823f3-99e2-4395-b336-5de6ff8c4cd2" alt="Arduino setup" width="400" />
   </div>
   
## Features
- **Bootloader Programming**: Burn bootloaders to ATmega328P.
- **HEX File Upload**: Easily upload firmware files.
- **Code Protection**: Option to lock the code as write-only.
- **HEX File Read**: Save existing HEX code from the IC.

## Requirements
- **USBasp Programmer**
- **USBasp Drivers**: [Download from USBasp](https://www.fischl.de/usbasp/).
- **Atmega_Programmer**

## Instructions

### Hardware Setup
Connect the USBasp programmer to an Arduino or AVR circuit with an ATmega328P IC.

<div style="text-align: center;" >
    <img src="https://github.com/user-attachments/assets/96235653-977a-4d52-b15f-227c8c991c83" alt="Arduino setup" width="300" />
    <img src="https://github.com/user-attachments/assets/aadfddd7-835a-4722-aa79-510cce48aad2" alt="AVR circuit setup" width="300" />
</div>

### Burn Bootloader
1. Open your programming software.
2. Select **usb** as the Port.
3. Click **Burn**.

### Upload HEX File
1. Choose a HEX file.
2. Click **Write**.
3. *(Optional)*: Select **Lock** to make it write-only.

### Read HEX File
1. Create and name a file.
2. Click **Read** to copy HEX code from the microcontroller.
3. Save the file if readable.

## License
................................................

## Contributing
Feel free to open issues or create pull requests to enhance the tool.

