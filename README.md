# Compit Nano Color 2 esphome

Esphome RS485 config for Compit Nano Color 2.

Entities names are in Polish, as far as I can tell this ecosystem is available only in Poland. 

This controller is used in ventilation units by Polish manufacturers, in my case it's ECS Piotr Paruszewski / o3ozon.

<img src="/ha.png" width=300>
<img src="/ha-debug.png" width=300>

## Warning

I divided the entities into those necessary for mechanical ventilation with heat recovery and debug, where all registers from the manufacturer's documentation are listed. 

In my case, the sensors had different addresses than described, so I assume it's necessary to use trial and error to determine which register represents the actual information in a given implementation.


## Hardware

I used [m5stack ATOM Lite with RS485 module](https://shop.m5stack.com/products/atom-rs485-kit) but any ESP32/ESP8266 with RS485 to ttl will do.

It's a great module because it can be powered directly from the Nano Color2.

![Nano Color 2 with Atom](/nanocolor2.jpg)



