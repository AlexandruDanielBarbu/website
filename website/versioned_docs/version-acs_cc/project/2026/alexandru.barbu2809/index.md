# Automotive Black Box
A black box that logs data on an SD card if the RC car has been in an accident.

:::info 

**Author**: Barbu Alexandru Daniel \
**GitHub Project Link**: TODO

:::

<!-- do not delete the \ after your name -->

## Description

The project will do 2 things:
1. Detect if the RC car was involved in a crash
2. If a crash had occurred log data such as acceleration, speed etc on an SD card.

## Motivation

I am passionate about cars. Many of my solo projects had involved cars from modeling to simulating the forces that act on a car.

## Architecture 

Add here the schematics with the architecture of your project. Make sure to include:
 - i will do a Kalman filter so i need a crate for handling math and matrix multiplication
 - i will have to do some custom graphs to determine when an accident happened so another rust crate there
 - from what i understand i also need a filter that stabilizes the signal from the IMU sensor

TODO:
 - what are the main components (architecture components, not hardware components)
 - how they connect with each other

## Log

<!-- write your progress here every week -->

first 2 weeks: finding the idea

week 3: validating idea

week 4 to present day: mess around with the board, the labs, order parts, waiting for parts.

### Week 5 - 11 May

### Week 12 - 18 May

### Week 19 - 25 May

## Hardware

Components:
 - IMU 6 axis
 - MicroSD card module
 - STM board (provided by the university)
 - buzzer
 - LED
 - wires
 - breadboard
 - power supply 4 AA batteries

### Schematics

Place your KiCAD or similar schematics here in SVG format.

### Bill of Materials

<!-- Fill out this table with all the hardware components that you might need.

The format is 
```
| [Device](link://to/device) | This is used ... | [price](link://to/store) |

```

-->

| Device | Usage | Price |
|--------|--------|-------|
| [Raspberry Pi Pico W](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html) | The microcontroller | [35 RON](https://www.optimusdigital.ro/en/raspberry-pi-boards/12394-raspberry-pi-pico-w.html) |


## Software

| Library | Description | Usage |
|---------|-------------|-------|
| [st7789](https://github.com/almindor/st7789) | Display driver for ST7789 | Used for the display for the Pico Explorer Base |
| [embedded-graphics](https://github.com/embedded-graphics/embedded-graphics) | 2D graphics library | Used for drawing to the display |

## Links

<!-- Add a few links that inspired you and that you think you will use for your project -->

1. [link](https://example.com)
2. [link](https://example3.com)
...
