# MQTT Plugin for CraftBeerPi 3.0

This plugins allows to connect to an MQTT Message broker to receive sensor data and invoke actors.

## Installation

After installation please install python MQTT lib paho

´´´pip install paho-mqtt´´´

https://pypi.python.org/pypi/paho-mqtt/1.1

Second step is to install an MQTT message broker on your pi.
An open source message broker is mosquitto (https://mosquitto.org/)

´´´
sudo apt-get update
sudo apt-get install mosquitto

sudo service mosquitto status
Starten und Stopen geht so
sudo service mosquitto stop
sudo service mosquitto start
´´´