---
title: 'IoT + ML + Web PWA'
description: 'First Full Stack Project'
pubDate: 'Nov 15 2023'
heroImage: 'https://bafkreiapok6ktjw3ssqputp4352jozlg4cwdb75f2qexabio5afzpgpd6u.ipfs.nftstorage.link/'
---

## Project Origin

As I needed to get a job in tech, I would need at least a traiing certificate to get into a job. I joined an immersive bootcamp 
in Late 2019 for reinforceing my Machine Learning skill and cooperating with makers from around the world.

I had done several projects during that period: Text2Img AI Generator, Game Stategy Analysis for MMOOC, Objective detection for movie, and an IoT module with Deep Learning capacity.

The ideas originated from the common injuries on foot in my team, so we decided to create a module that users can wear on foot and analyze if potential illnesses exists. The module includes a ESP WiFi module, a pair of resistance sensors, a PCB, a raspberry pi 4 B, a pair of sensor stabilizers, and the software components, which includes a Linux server, nodeRed module, and a Computer Vision model in Tensorflow.

How it works?

A user will wear a pair of smart soles embedded with those sensors. Those sensors will be connected to the Wifi module and PCB. So, whenever that user walks, runs, or even sqauts with the module, the resistance sensors will send data point to the linux server via the PCB module, then those data will be preprocessed as wave length image per second which finally consumed by the Computer Vision model. 