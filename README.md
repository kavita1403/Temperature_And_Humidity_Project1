# Temperature_Humidity_Monitoring

## Description:-
In this project,the current humidity and temperature data is shown over the internet using the ThingSpeak Server.
It is accomplished by the data communication between Arduino,DHT11 Sensor Module,ESP8266 Wi-Fi Module.
Celcius scale thermometer and percentage scale humidity meter displays the ambient temperature and humidity
on ThingSpeak Server for live monitoring from anywhere in the world.

## Required Component:-
* Arduino Uno
* DHT11
* ESP8266 Wi-Fi Module
* Jumper Wires
* Breadboard

## Circuit-Diagram:-

<img src="https://lh3.googleusercontent.com/Gf6gDP9fea6isB4Ck6l-gIf0AqQ7QmVQ-afXxsRknJ2hjWtZfYtm7TFuOafjMphxXfqP3xc=s113">
<img src="https://lh3.googleusercontent.com/H3xmtaU9vDSjnEorhKYukTh59-ThRdpbCXqvHvdl9Kk3PEnYJZ_IldAFLSRvhympT9OFNw=s126">






## Functioning:-
* Humidity and Temperature sensor DHT11 senses the humidity and temperature data.
* Arduino Uno extracts the DHT11 sensor's data as suitable number in percentage and celcius scale
and sends it to Wi-Fi module.
* Wi-Fi module ESP8266 sends the data to ThingSpeak's server.
* finally,ThingSpeak analyses the data and shows it in a graph form.






