# Zigbee2MQTT + Mosquitto Docker Compose
A full Zigbee2MQTT stack including Mosquitto in a docker-compose file.

Thanks to @Koenkk for creating Zigbee2MQTT!

It should be as simple as:
```
git clone https://github.com/sknalbsivraj/zigbee2mqtt_docker-compose.git zigbee2mqtt
```

```
cd zigbee2mqtt
``` 

```
Edit the .env file:

root_dir = /FOLDER/TO/STORE/CONFIGS
timezone = Europe/London
device = ttyUSB0
```
```
docker compose up -d
```
This should get you up and running!
