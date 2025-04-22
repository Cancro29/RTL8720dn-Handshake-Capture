# RTL8720dn-Handshake-Capture
Capture WPA/WPA2 4-way handshake using BW16 (RTL8720dn)

## Fork Information
This code is a fork of Nickguitar's code. https://github.com/Nickguitar/cypher-5G-deauther <br>
This code also uses tesa-klebeband's wifi packet injection code. https://github.com/tesa-klebeband/RTL8720dn-WiFi-Packet-Injection <br>
I did web server stuff for simplicity<br>
This code also demonstrates the capability of RTL8720dn performing SoftAP, promiscuous mode, and deauth at the same time (sort of). <br>

## Installation
This program can be compiled using AmebaD SDK version 3.1.7 <br>
Because I modified some of the core libraries, you may encounter a problem. Please let me know so I can fix it. <br>

## Important
You may need to use this board definition or compilation will fail : https://drive.google.com/file/d/13FOQ47H48j42ArYKcxLlSIuS7eU7qN_B/view?usp=sharing
## How To Use
1. Compile and flash the code
2. Connect to "CAPPER" with password "12345678"
3. Go to 192.168.1.1 in your browser
4. Select your target
5. Press Capture Handshake
6. Wait for a while
7. If the handshake is captured, Capture Handshake button will change to Get PCAP

## WARNING
Performing such attacks is ILLEGAL in most places. Make sure you are using it on controlled environment and NOT in public places.
