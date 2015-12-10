# tendoon
Connector for your GPIOs to messages protocols

## Target

We want to find an easy way, to use GPIOs of IoT Devices to make them accessible from your favorite programming language or over your network.

## Idea

Tendoon is a collection of node.js oder similar libraries for IoT Devices like Arduino, Raspberry Pi, Merkurboard, Tessel ... It will give you the possibility to connect your GPIOs to common messages protocols.

## Supported messages protocols

* MQTT
* MQTT-SN
* CoAP
* HTTP Rest

## How should it work?

Start Tendoon, select your IoT device, connect your GPIOs to your message, download your tendoon to your device, ready.

## Example

For Raspberry Pi

>> GPIO07 --> /gpio07/input --> /startbutton, 0: not_pressed, 1: pressed
>> GPIO14 --> /gpio14/output --> /led/run, 0: off, 1: on, attribute: color: green.

