# fan-card4
A four speed fan control for Home Assistant's Lovelace

This is javasctipt code for a four button fan control in Home Assistant. 
It was built specifically for the TreatLife Esmlfe Fan controller, burned with Tasmota fo run via and MQTT broker.

Install steps:
1) Place this code in the proper directory (commonly make a new directory, e.g., /www/fan-card4).
2) Make sure you register this code in Lovelace (Lovelace Hamburger Menu - Manage Resources, add this resource (e.g.,  /www/fan-card4/fan-card4.js)
3) Force hard reset to browser (Ctrl-F5 in Chrome-type browsers)

Example Lavelace code for this Lovelace Card is as follows: 
  - entity: fan.MyTasmotaTreatLife
    icon: mdi:fan
    name: Fan
    customTheme: true
     type: custom:fan-card4
 
 customTheme indicates active fan speed as green, off is red.
