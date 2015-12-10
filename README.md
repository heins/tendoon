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

For Raspberry Pi and MQTT (uses JSON-LD)

> GPIO07 --> topic: /gpio07/input --> topic: /startbutton/state, 0: not_pressed, 1: pressed, attribute: port: digital_input
> GPIO14 --> topic: /gpio14/output --> topic: /led/run/state, 0: off, 1: on, attribute: color: green, port: digital_output

## Usage

Use your message together with BEAM.

## Public or Private

Define whether your message should be accessible local on your IoT Device or global over your network:

> Private -> Local Access
> Public -> Global Access

## Defining your IoT Devices

For Tendoon we will use a simle descrition language to define the interface and habit for IoT devices or Cyber Physical Systems,

## Notice

The GUI of Tendoon should be seamlessly integrated into MAIER - Programming Things.

