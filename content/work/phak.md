---
title: "PHAK: Programmable HAptic Knob (WIP)"
description: ""
date: 2023-11-26T02:51:22.450Z
draft: false
tags:
  - electronics
  - product-design
  - prototyping
  - rp2040
  - work
  - wip
weight: 10
images:
  - /images/PHAK/phak_digital.png
  - /images/PHAK/phak_analog.png
multipleColumn: true
url: ""
hideTitle: false
hideExif: true
hideDate: true
---
### Motivation
Throughout history, the primary competency of musicians was tactile. The act of playing an instrument was felt, learned as a type of muscle memory. A concert was an interaction not just between the artist and the music, but between the reactions of the instrument and the touch of the hands. 

Most electronic instruments are not like this. Modal interfaces, passive buttons, and non-reactive sliders cannot be learned through tactility.

{{% flex "mt-5 flex-wrap" %}}
{{%column "flex: 1 1 200px"%}}
The PHAK ---which is short for **P**rogrammable **HA**ptic **K**nob--- is a synthesizer module that uses a Brushless DC Motor to provide computer controlled haptic feedback to the user as they use the device.

Currently, I am working on the audio processing section. The circuit has to handle 6 inputs and 6 outputs across a -5 to +10V range. This is the most complicated part of the control combining analogue and digital systems through Digital Signal Processing.
{{%/column%}}
{{%column "flex: 1 0 300px"%}}
![The circuit board for the PHAK](/images/PHAK/phak_on_grass.jpg)
{{%/column%}}
{{%/flex%}}

![Schematic of the design](/images/PHAK/schematic.png "Schematic of the design so far")