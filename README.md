# zigbee2mqtt docker-compose
A full Zigbee2MQTT stack including Mosquitto in a docker-compose file.

Thanks to @Koenkk for creating Zigbee2MQTT!

It should be as simple as:
```
git clone https://github.com/Jarvis-1487/zigbee2mqtt_docker-compose.git zigbee2mqtt
```

```
cd zigbee2mqtt
``` 

```
docker compose up -d
```

This should have you up and running. (Works for me)

I think the only thing you may need to change is your adapter in the Zigbee2MQTT config (ACM0 or USB0).
