# Temperature_Humidity_project

## Description:-
In this project,the current humidity and temperature data is shown over the internet using the ThingSpeak Server.
It is accomplished by the data communication between Arduino,DHT11 Sensor Module,ESP8266 Wi-Fi Module.
Celcius scale thermometer and percentage scale humidity meter displays the ambient temperature and humidity
on ThingSpeak Server for live monitoring from anywhere in the world.

## Required Component:-
* Arduino Uno
* DHT11
_ ESP8266 Wi-Fi Module
_ Jumper Wires
_ Breadboard

## Circuit-Diagram:-
<img src="C:\Users\pcm1\Pictures\Screenshots\WhatsApp Image 2020-12-21 at 4.51.22 PM (2).jpeg">






## Functioning:-
_ Humidity and Temperature sensor DHT11 senses the humidity and temperature data.
_Arduino Uno extracts the DHT11 sensor's data as suitable number in percentage and celcius scale
and sends it to Wi-Fi module.
_Wi-Fi module ESP8266 sends the data to ThingSpeak's server.
_finally,ThingSpeak analyses the data and shows it in a graph form.






