# zigbee2mqtt docker-compose
A full Zigbee2MQTT stack including Mosquito in a docker-compose file.
Thanks to @Koenkk for creating such a great bit of code!

Create the directories in /home/USER to make it easy to manage:
(replace USER with your username)
```
mkdir /home/USER/{zigbee,mqtt}
```

Move ```mosquitto.conf``` into ```/home/USER/mqtt/``` 

Move ```configuration.yaml``` into ```/home/USER/zigbee/configuration.yaml``` 

Run ```docker compose up -d``` to bring up the containers.

This should have you up and running. (Works for me)
