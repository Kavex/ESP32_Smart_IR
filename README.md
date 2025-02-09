# ESP32_Smart_IR
Smart IR for ESP32

**What You need**

* ESP32 Development Board
* Arduino IDE
* IRremoteESP8266 Lib
* TL1838 Infrared Receiver
* Diymore PCB0100 Infrared Transmitter or another 3.3v compatible Infrared Transmitter
* Cables!!!!
* Breadboard for testing!!!!
* ESP32 Terminal Adapter for testing!!!!

-----

**How to get IR Codes:**

Using a TL1838 Infrared Receiver you can get the IR codes from your remotes on Pin 14

 ![image](https://github.com/user-attachments/assets/87f99944-d237-4088-a1da-7a1b9a7aedc1)

![image](https://github.com/user-attachments/assets/09b41787-d34f-4459-b06d-60ff8ecec524)

![image](https://github.com/user-attachments/assets/ae272a62-c4e8-48ee-a2db-2e6d39295800)

ESP32 Code under Testing\IR_ReceiverTest\IR_ReceiverTest.ino

Once the code is uploaded to your ESP32 you can use Serial Monitor in Arduino IDE to check the output

You can change the pin if you want in the code. not all pins work so best to look it up. 

** Example Codes **

Samsung DVD Player Codes

Power:0x2D51D3B4

Vol+:0x15D943B8

Vol-:0x2D4F7194

Mute:0xA5A1E0F8

Function:0xCA949638


LG TV Codes

Power:0x20DF10EF

Vol+:0x20DF40BF

Vol-:0x20DFC03F

Input:0x20DFD02F

-----

**How to send IR Codes:**

I used a Diymore PCB0100 Infrared Transmitter because it's easy but you could use a regular ir transmitter led with a resistor 

![image](https://github.com/user-attachments/assets/9d76809a-7b43-4ce3-8907-c0de8dc1515e)

ESP32 Code under Testing\IR_TransmitterTest\IR_TransmitterTest.ino

edit the defined code and test it out.

-----

**How to turn it smart:**

Working on this part, stay turned

-----
  
