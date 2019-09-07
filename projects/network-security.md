---
layout: project
type: project
image: images/micromouse.jpg
title: Drone Traffic Profiling and Protocol Reverse Engineering
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2018-01-09
labels:
  - Wireless Networking
  - Network Security
  - Python
summary: My team is developing a toolset to classify and profile Unmanned Aerial Systems (UASs) based on their unique wireless communication methods.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

I am currently analyzing wireless network traffic and adapting current software using packet analysis for UAS classification and profiling for my senior design project.
• Capturing wireless network traffic from drone using aircrack-ng suite
• Decrypting WPA2 packets using Wireshark
• Introduced to Netzob library for interpretation and reverse engineering of wireless packets
• Modifying Python scripts for statistical analysis of wireless data following the MAVLink protocol

In previous semesters with this project, I gained familiarity with the Aircrack-ng suite and related tools using the Kali Linux operating system. (ENGR296/396 credit)
• Cracked WEP, WPA/2 encryption with aircrack-ng suite.
• Bypassed hidden SSID and MAC filtering.
• Used different flaws in wireless protocol to gain access to controlled network. Includes Cafe Latte, Man-in-the-Middle, Hirte, Mis-Association/Honeypot attacks.

Here is some code that illustrates how we read values from the line sensors:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



