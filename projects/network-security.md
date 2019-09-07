---
layout: project
type: project
image: images/uas-banquet.jpg
title: Network Profiling and Protocol Reverse Engineering
permalink: projects/uas-security
# All dates must be YYYY-MM-DD format!
date: 2018-01-09
labels:
  - Wireless Networking
  - Network Security
  - Python
summary: My team is developing a toolset to classify and profile Unmanned Aerial Systems (UASs) based on their unique wireless communication methods.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/uas-david.JPG">
  <img class="ui image" src="../images/uas-wireshark.JPG">
  <img class="ui image" src="../images/uas-main.JPG">
</div>

<hr>

I am currently analyzing wireless network traffic and adapting current software using packet analysis for Unmanned Aerial System (UAS) classification and profiling for my senior design project.

With Kali Linux, I use the aircrack-ng suite to capture wireless network traffic from various UASs that support WPA2 encryption. We can examine more information about the network traffic in the form of packets with the Wireshark application.

Last semester, we were introduced to the Netzob library for help with interpretation and reverse engineering of wireless packets. We also modified Python scripts for statistical analysis of wireless data following the wireless protocols.

We are currently analyzing trends in the collected data in network Layers 1, 2, 3.

<hr>

In previous semesters with this project, I gained familiarity with the Aircrack-ng suite and related tools using the Kali Linux operating system. (ENGR296/396 credit)

• Cracked WEP, WPA/2 encryption with aircrack-ng suite.

• Bypassed hidden SSID and MAC filtering.

• Used different flaws in wireless protocol to gain access to controlled network. Includes Cafe Latte, Man-in-the-Middle, Hirte, Mis-Association/Honeypot attacks.

Project Repo: <a href="https://github.com/saharama/UAVClassifier"><i class="large github icon "></i>saharama/UAVClassifier/</a>

