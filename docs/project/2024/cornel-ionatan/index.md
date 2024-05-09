# Morse Code spy device
A comunication device that lets you comunicate within the same network with another person through morse code.

:::info 

**Author**: Cornel Ionatan \
**GitHub Project Link**: https://github.com/UPB-FILS-MA/project-JoniHey100

:::

## Description

It should work similar to a walkie-talkie system. You can send the morse code message by pressing a button, and you can choose among 3 ways depending on how you want to receive the message: sound (buzzer), light (LED) or feel (vibration motor). Additionally i could implement translataion of the message and use a LCD which displays the message received into English alphabet.

## Motivation

I wanted a quick and quiet way of communicating basic messages between my friends. Working with audio systems and PA equipments we usually need to send short important messages and would like not to be observed by the whole gathering at church or conference. Messages like: volume up/ down, mute mic, next slide, etc.

## Architecture 

Add here the schematics with the architecture of your project. Make sure to include:
 - what are the main components (architecture components, not hardware components)
 - how they connect with each other

## Log

<!-- write every week your progress here -->

### Week 6 - 12 May

### Week 7 - 19 May

### Week 20 - 26 May

## Hardware

Detail in a few words the hardware used.

### Schematics

Place your KiCAD schematics here.

### Bill of Materials

<!-- Fill out this table with all the hardware components that you might need.

The format is 
```
| [Device](link://to/device) | This is used ... | [price](link://to/store) |

```

-->

| Device | Usage | Price |
|--------|--------|-------|
| [Rapspberry Pi Pico W](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html) | The microcontroller | [35 RON](https://www.optimusdigital.ro/en/raspberry-pi-boards/12394-raspberry-pi-pico-w.html) |
| [Rapspberry Pi Pico W](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html) | The 2nd microcontroller | [35 RON](https://www.optimusdigital.ro/en/raspberry-pi-boards/12394-raspberry-pi-pico-w.html) |
| 2 x [Buzzer](https://www.optimusdigital.ro/ro/audio-buzzere/12247-buzzer-pasiv-de-33v-sau-3v.html?search_query=buzzer&results=61) | Receiving signal through sound | 2 x [2 RON](https://www.optimusdigital.ro/ro/audio-buzzere/12247-buzzer-pasiv-de-33v-sau-3v.html?search_query=buzzer&results=61) |
| [Red LED](https://www.optimusdigital.ro/ro/optoelectronice-led-uri/29-led-set-3-culori-x-10-pcs-fiecare.html?search_query=led+albastru&results=66) | Receiving signal through light | [0.40 RON](https://www.optimusdigital.ro/ro/optoelectronice-led-uri/29-led-set-3-culori-x-10-pcs-fiecare.html?search_query=led+albastru&results=66) |
| [Blue LED](https://www.optimusdigital.ro/ro/optoelectronice-led-uri/29-led-set-3-culori-x-10-pcs-fiecare.html?search_query=led+albastru&results=66) | Receiving signal through light | [0.30 RON](https://www.optimusdigital.ro/ro/optoelectronice-led-uri/29-led-set-3-culori-x-10-pcs-fiecare.html?search_query=led+albastru&results=66) |
| 2 x [Vibration Motor](https://www.optimusdigital.ro/ro/motoare-motoare-cu-vibratii/86-motor-cu-vibratii-a1027.html?search_query=vibrat&results=53) | Receiving signal through vibrations | 2 x [10 RON](https://www.optimusdigital.ro/ro/motoare-motoare-cu-vibratii/86-motor-cu-vibratii-a1027.html?search_query=vibrat&results=53) |
| 2 x [Stereo Potentiometer](https://www.optimusdigital.ro/ro/componente-electronice-potentiometre/1886-potentiometru-stereo-10k.html?search_query=potentiometru&results=173) | For controlling the volume of buzzer and intensity of LED | 2 x [2 RON](https://www.optimusdigital.ro/ro/componente-electronice-potentiometre/1886-potentiometru-stereo-10k.html?search_query=potentiometru&results=173) |
| [LCD with Yellow-Green Backlight](https://www.optimusdigital.ro/en/lcds/62-1602-lcd-with-i2c-interface-and-yellow-green-backlight.html?search_query=lcd&results=257) | For showing the translated message | [15 RON](https://www.optimusdigital.ro/en/lcds/62-1602-lcd-with-i2c-interface-and-yellow-green-backlight.html?search_query=lcd&results=257) |
| [LCD with Blue Backlight](https://www.optimusdigital.ro/en/lcds/2894-1602-lcd-with-i2c-interface-and-blue-backlight.html?search_query=lcd&results=257) | For showing the translated message | [16 RON](https://www.optimusdigital.ro/en/lcds/2894-1602-lcd-with-i2c-interface-and-blue-backlight.html?search_query=lcd&results=257) |
| 2 x [Button]| For sending the message| |
| 2 x [Toggle switch] | For switching between outputs (LED, BUZZER, VIBRATION) | |

## Software

| Library | Description | Usage |
|---------|-------------|-------|

## Links

<!-- Add a few links that inspired you and that you think you will use for your project -->

1. [link](https://example.com)
2. [link](https://example3.com)
...
