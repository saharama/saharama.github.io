---
layout: project
type: project
image: images/uas/uas-banquet.jpg
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
  <img class="ui image" src="../images/uas/uas-david.JPG">
  <img class="ui image" src="../images/uas/uas-wireshark.JPG">
  <img class="ui image" src="../images/uas/uas-main.JPG">
</div>

<hr>

As an Undergraduate Research Assistant for Dr. Yingfei Dong, I am part of a team working towards classifying Unmanned Aerial Systems (UASs) based on their wireless network communication patterms. I am currently analyzing wireless network traffic and developing Python scripts for network packet analysis of UASs. This is a continuation of my senior design project, as we are continuing to expand the accuracy and breadth of our UAS Classifier scripts. We are also beginning to delve into the realm of *machine learning*, as our newly proposed tool seeks to use pattern recognition in network traffic to automate the classification of drones.

In previous semesters with this project, I gained familiarity with the Aircrack-ng suite and related tools using the Kali Linux operating system. With guidance I was able to crack WEP, WPA/2 encryption with aircrack-ng suite. In addition, we bypassed hidden SSID and MAC filtering. Most importantly, we used different flaws in wireless protocol to gain access to controlled networks. This includes well known Wi-Fi encryption attacks including Cafe Latte, Man-in-the-Middle, Hirte, Mis-Association/Honeypot attacks. The main goal was to build a firm foundation of wireless networking knowledge to later be implemented in our senior design projects. Now, using Kali Linux, I use the aircrack-ng suite to capture wireless network traffic from various UASs that support WPA2 encryption. We can examine more information about the network traffic in the form of packets with the Wireshark application.

<img class="ui large centered rounded image" src="../images/uas/uas-shaka.jpg">

In the first semester my senior project, we were introduced to the Netzob and Scapy library for help with interpretation and reverse engineering of wireless packets. My team was responsible for modifying Python scripts for statistical analysis of wireless data following specified wireless protocols. We began to analyze trends in the collected data in network Layers 1, 2, 3.

It was interesting, to me, how this project and my former part-time job in the UH Data Center would end up falling hand-in-hand. I feel like my part-time job helped to give me a firm, physical view of networking. I also learned a lot about networks from my coworkers, who would spend time helping me to understand concepts like the OSI-model. Before you can make a network secure, you first need to truly understand how it works.

For my senior design project, I worked as part of a team to develop a proof-of-concept UAS classifier. We managed to build wireless profiles for two drones, and we were able to distinguish between the two based on sets of wireless data collection samples. These results were based purely on encrypted traffic, where we looked at the timing and sizing of different characterisitc packets. In my continued work as a Research Assistant, my sub-team is now focused on examining the decrypted data trends of different drones. We have been focusing on MAVLink data parsing, as different drones package information with slight variations.

After taking ICS314, we are working on transitioning to use *Agile Project Management* techniques for setting specific goals, breaking down work into tasks, and communicating much more effectively. As we already have a Github Organization, we are looking to use the convienient Kanban project board in our respective Github repository.

Project Repo: <a href="https://github.com/saharama/UAVClassifier"><i class="large github icon "></i>saharama/UAVClassifier/</a>
