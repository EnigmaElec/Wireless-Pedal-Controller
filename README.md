# Wireless-Pedal-Controller
Firmware Flasher

![](https://github.com/EnigmaElec/Wireless-Pedal-Controller-Windows/blob/main/images/pedal.jpeg)


# How to :
1. Download Files or use git clone https://github.com/EnigmaElec/Wireless-Pedal-Controller-Windows.git </br>
2. Put Folder into Desktop</br>
![File content is like this : ](https://raw.githubusercontent.com/EnigmaElec/Wireless-Pedal-Controller-Windows/refs/heads/main/images/File%20Content.bmp)</br>
3. When you get update files put in folder Update 3.bin Files and run WPC.exe
4. Or if you Want to Restore the original firmware use Original_flasher.exe
5. All the step is identical, only the exe files is diff     
6. Make sure Pedal_RX_original folder is not empty and check Port in Device Manager where device is connected</br>
![See in Green bracket, the directory and the COM port](https://raw.githubusercontent.com/EnigmaElec/Wireless-Pedal-Controller-Windows/refs/heads/main/images/Original%20Flasher.bmp)</br>
5. Set Baudrate as desire by default the baudrate is 921600</br>
![Baudrate can be Change or use default baudrate](https://raw.githubusercontent.com/EnigmaElec/Wireless-Pedal-Controller-Windows/refs/heads/main/images/baudrate.bmp)</br>
![Flashing Progress](https://raw.githubusercontent.com/EnigmaElec/Wireless-Pedal-Controller-Windows/refs/heads/main/images/flashing%20progress.bmp)</br>
![Flashing is complete](https://raw.githubusercontent.com/EnigmaElec/Wireless-Pedal-Controller-Windows/refs/heads/main/images/Complete.bmp)</br>
   
# Troubleshoot
1. When Device not detected in Device Manager check the USB cable make sure it has 4 wire V+ D+ D- And GND
2. Flashing Error Check 3 Binary files in correct folder and the Exe is right ( next Check Python path and esptool is installed)
3. See Error during Flashing ( Reset Device in left hole from the top view) and flash it again)
4. Device is not detected and flashing err (Contact supplier for further information)
