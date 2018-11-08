# rpi3B-MQTT
some memo. for install MQTT brocker @ RPI3B

## install

- sudo apt-get install mosquitto mosquitto-clients

- 確認mosquitto是否執行 （預設安裝完會自動執行）

## subscript a topic

- mosquitto_sub -t malo-iot/T

## push a topic

- mosquitto_pub -t malo-iot/T -m 12

## push a topic to an address

- mosquitto_pub -t malo-iot/T -m 25 -h iot.eclipse.org -p 1883

