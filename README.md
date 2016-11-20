# smart-loadCell
A smart load sensor with RFID for inventory management. 
The embedded system first obtains of the product details via RFID tags and then obtains the weight using load cell.
The system then transfers the weight+productDetails to the ESP8266 module serially which in turn transmitts the data to a cloud server
for keeping a log of the inventory as well as to an Android app.

This project won the third place in SSN IoT Hackathon
