# OpenPupil
Instuctions for assembly and/or fabrication of our open-source pupilometer.

# Overall system architecture
The overall system design can be seen in our poster presented at ARVO 2017 (https://www.arvo.org/AM/) here.
Our OpenPupil electronic system consists of: a Raspberry Pi 2 B+, with a NoIR camera, two 850nm IR LEDs, a 16 neopixel ring, USB wireless dongle, microSD card . 
Our hardware system consists of: a 3D printed eyepiece, a lazercut enclosure, a Google Cardboard lens
Our software system consists of: a python flask server, a supervisor instance, a C library and program for image collection and processing
A tabulated series of the above components is available below along with prices and purchasing suggestions.
For setup you will also (unless you're proficient with SSH and command line) need an HDMI cable, usb keyboard and mouse.

# Hardware instructions
You can find the lazercut enclosure designs (for 6mm acrylic) here.
You can find the `.stl` file for the 3D printed eyepiece here. Alternatively, if you do not have access to a 3D printer, you can purchase a printed one directly from our Shapeways store here (www.shapeways.com/shops/openpupil).

# RPi Installation instructions
`sudo apt-get install supervisor python-picamera`
`sudo pip install flask`

# Components

| Component     | Cost (USD)         | Purchasing Link |
| ------------- |:-------------:| -----:|
| RPi v2 B+ | $29.95 | https://www.adafruit.com/product/1914 | (a full kit can be purchased here: https://www.adafruit.com/product/2380)
| No IR camera | $29.95 | https://www.adafruit.com/product/387 |
| 850nm IR LEDs * | $0.75ea | https://www.adafruit.com/product/387 |
| Neopixel Ring | $9.95 | https://www.adafruit.com/product/1463 |
| USB Wifi Dongle | $11.95 | https://www.adafruit.com/product/814 |
| microSD card (8 or 16GB)| $14.95 | https://www.adafruit.com/product/1583 |
| 3D printed eyepiece | $ | |
| Google Cardboard v1 lens | $ | |

# Contact Details
This project is currently lead by Dr. Jesse Gale (jesse.gale@gmail.com) with support from Elf Eldridge (kaiwhata@gmail.com) and honours student Shaetrun Pathmanathan.
