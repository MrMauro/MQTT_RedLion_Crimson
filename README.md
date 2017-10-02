# MQTT_RedLion_Crimson
MQTT driver for the RedLion Crimson 3.0

This is an implementation of the MQTT protocol for devices programmed with RedLion Crimson 3.0 http://www.redlion.net/crimson-30

To test it:
- The broker has hardcoded the current ip of test.mosquitto.org. You may want to change it.
- Configure and use Crimson Emulator (Set a propper Ethernet mapping). It is based on G306A device
- Use a MQTT Client like http://mqttfx.jensd.de/index.php/download to help with the test
- The Program Start fill the tags used to provide a basic configuration. It subscribes the device to ToRL and its predefined Pubish Topic is FromRL

This documention is on the works... If doubts, please ask.

Please note that currently this is considered in alpha stage, so future versions can lead disruptive changes to implementations based on this version.

Important limitations:
- It does not support User/Password, Will, Clean Session
- It does not provide error info on Connection neither the Session Present flag

*******************************************************************************
Copyright (c) 2017 VIDAL & ASTUDILLO Ltda 2017
www.vidalastudillo.com

All rights reserved. This program and the accompanying materials are made 
available under the terms of the GNU GENERAL PUBLIC LICENSE Version 3 which can
be found at https://www.gnu.org/licenses/gpl-3.0.txt

Contributors:
   MAURICIO VIDAL - initial API and implementation and/or initial documentation