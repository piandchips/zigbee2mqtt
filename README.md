# zigbee2mqtt_docker_compose
A full Zigbee2MQTT stack including Mosquito in a docker-compose file.

Create the directorys in /home/USER to make it easy to manage:
(replace USER with your username)
```
mkdir /home/USER/{zigbee,mqtt}
```

Run ```docker compose up -d``` to bring up the containers and create neccessary files.

Stop the containers ```docker compose stop```.

**Edit ```mosquitto.conf```.**
```
nano /home/alex/mqtt/conf/mosquitto.conf
```

Add the following:
```
persistence true
persistence_location /mosquitto/data/
log_dest file /mosquitto/log/mosquitto.log
listener 1883
allow_anonymous true
```

Finally start your containers again:
```
docker compose up -d
```

This should have you up and running. (Works for me)
