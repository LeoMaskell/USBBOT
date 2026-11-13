---
title: "USBBOT"
github: "https://github.com/LeoMaskell/USBBOT"
description: "custom usb logic analyser"
created_at: "2026-10-04"
total_time: "7h"
---

# October 15, 2026: desigbned the schematic for the PCB with kicad!
<!-- fabricate:entry 493 -->

OMG WTH that is SOOO hard
- using a bare RP2040 chip and all the components i need to make it work
- first time not just using a prebuilt microcontroller like the pi pico

![](https://fabricate.hackclub-assets.com/3a6a490a81f7a81bad73e5068da5b15056d3abb8a502f2bf3704bdc096b376f2/image-png/image.png)

- im working on the actual layout but having LOADS of issues
![](https://fabricate.hackclub-assets.com/8f41458c197f96c4bae4d377424eae6d33de7dac42fc8f281aad3838e2fe3c18/image-png/image.png)


## wierd things  i encountered while making it:
- i didnt realise you need more than just the rp2040, you need a power chip, and a storage chip, but not external ram?
turns out that rp2040 has internal 216kb of ram baked into it
- i didnt realise that you need a 12Mhz crystal oscillator to make it turn on too!
- since when have raspberry pis had analogue pins???!!!!!
- apparently i need to have stuff in specific places so they dont become ***RADIO ANTENNAS*** WTAF LIKE BRUH

**Total time spent: 2h 30m**

# November 13, 2026: finnished the first version of the PCB
<!-- fabricate:entry 2928 -->

## finnished the first version of the PCB!
![](https://fabricate.hackclub-assets.com/26c11585cf3e45a278425bbe744ca77360bbfb05e6107d7805973421374b3a2e/image-png/image.png)
![](https://fabricate.hackclub-assets.com/f17de11f59077550bd12a6b4ad45fbf00a80da0ef4cbd88045007e1043d487f4/image-png/image.png)

## good stuff about it:
- ***some*** cool silkscreens (not enough)
- *might* work
- has all essential components mapped out

## the bits that make V1 of the PCB rubbish:
- it wont work realistically
- the wrong capacitors
- **MORE SILKSCREENS!** 😘

## crazy stuff I found out:
- turns out electroltic can capacitors arent as effective at all for the high frequency stuff that a rp2040 outputs as a ceramic capacitor is
- its really hard to do a custom PCB that works without a prebuilt dev board😭😭😭

**Total time spent: 4h 30m**
