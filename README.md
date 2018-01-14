# Alexa Shades
**Forked from Makersmusings fauxmo library.  The WifiManager portion was contributed by Tapzu and the RF_Record portion by SillyFrog. These repositories can be found at the following links:

https://github.com/makermusings/fauxmo

https://github.com/tzapu/WiFiManager

https://github.com/sillyfrog/RFreplayESP

### Summary

This code allows the basic control of the bofu window motors using the following components:

1.) 12V Bofu Windo Motor

2.) NodeMCU 12E

3.) 5v-RF transmitter and receiver

### Design Notes
-Control of the Bofu roller shade motors is limited to on and off states.  On translate to having the shades down and off to having them open as written.

-The NodeMCU requires a 2.4 GHZ wireless connection. It will not work through 5 GHZ.

-The Wifimanager library was added to eliminate the need to manually configure a user name and password into the file if changes wireless access points. 

-If the NodeMCU cannot connect to the network the ESP xxxxx will apear in the list of available wireless networks for reconfiguration.
Links to thingy verse to be provided for the print of an enclosure for the NodeMCU.

### Instructions

The AlexaShadesBofu.ino can be downloaded and transfered to the NodeMCU using the arduino IDE. Before transfering the files the code will need to be updated with the correct RF codes for your particular remote.  Detailed instructions for decoding the Bofo remotes up and down codes will be provided in the Wiki.
