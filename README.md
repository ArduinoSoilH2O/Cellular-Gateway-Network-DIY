# Cellular-Gateway-Network
This repository contains materials related to the Node and Cellular Gateway soil moisture data logging network developed by USDA ARS researchers in 2018 for the Conservation Innovation Grant (CIG) Cover Crop Project. This project is in collaboration with North Carolina State University, University of Georgia Athens and the University of Maryland College Park. 

This Arduino-based wireless data logging system based on a Gateway-Node network monitors soil water at multiple sites concurrently.  

Nodes collect data from SDI-12 compatible TDR-based soil water sensors installed at multiple depths in the soil profile, a temperature sensor below a cover crop residue decomposition bag and a relative humidity sensor. Data from the sensors are stored to an on-board microSD card and then transmitted to the Gateway via LoRaTM radio transmitters embedded in the microcontrollers. 

The Gateway receives and saves the transmitted data to its on-board microSD card and sends the data to a web host server (ThingSpeak) via a 3G cellular module included on the device.
