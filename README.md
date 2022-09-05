# RFID

Based on this tutorial:
https://pimylifeup.com/raspberry-pi-rfid-rc522/


SDA connects to Pin 24.
SCK connects to Pin 23.
MOSI connects to Pin 19.
MISO connects to Pin 21.
GND connects to Pin 6.
RST connects to Pin 22.
3.3v connects to Pin 1.


Configure SPI interface:
`sudo raspi-config`


Install dependencies:
`
sudo apt install python3-dev python3-pip
sudo pip3 install spidev
sudo pip3 install mfrc522

`
