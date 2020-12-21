#Temperature_Humidity_project

##Description:-
In this project,the current humidity and temperature data is shown over the internet using the ThingSpeak Server.
It is accomplished by the data communication between Arduino,DHT11 Sensor Module,ESP8266 Wi-Fi Module.
Celcius scale thermometer and percentage scale humidity meter displays the ambient temperature and humidity
on ThingSpeak Server for live monitoring from anywhere in the world.

##Required Component:-
1-Arduino Uno
2-DHT11
3-ESP8266 Wi-Fi Module
4-Jumper Wires
5-Breadboard

##3>Circuit-Diagram:-







##4>Functioning:-
1-Humidity and Temperature sensor DHT11 senses the humidity and temperature data.
2-Arduino Uno extracts the DHT11 sensor's data as suitable number in percentage and celcius scale
and sends it to Wi-Fi module.
3-Wi-Fi module ESP8266 sends the data to ThingSpeak's server.
4-finally,ThingSpeak analyses the data and shows it in a graph form.






