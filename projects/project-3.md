---
layout: project
type: project
image: images/HIDRA.png
title: HI-DRA
permalink: projects/HIDRA
date: 2017
labels:
  - Java
  - Android
  - GitHub
  - Git
  - Mapbox
summary: A proof-of-concept Android application with the goal of providing first responders to natural disasters extra actionable information.
---

<img class="ui medium right floated rounded image" src="/images/HIDRA.png">

During the summer of '17 I worked on a team of six interns for Booz Allen Hamilton as a part of their annual Summer Games Challenge. For the challenge, we were tasked with taking an idea created by our project manager, and turning it in to a proof of concept to showcase to Booz Allen Hamilton senior leadership at the end of summer to acquire the funding and support needed to develop it in to a complete solution.

The idea in a nutshell was this: a system that both improves situational awareness for responders in military or humanitarian assistance and disaster relief (HADR) scenarios and after action reporting through use of historically collected data.

From this idea spawned HI-DRA (Humanitarian Assitance and Disaster Relief). HI-DRA was an application that collected information on surrounding wireless devices over various technologies such as Bluetooth, Bluetooth Low Energy, NFC, and RFID and visualized the data.

I acted primarily as one of the three Android developers for HI-DRA. I was responsible for designing the software architecture of the application at the start. There were many components of the app that we needed to work on simultaneously, so I made the project as modular as possible. I was also responsible for implementing our Bluetooth discovery service, a service that would periodically discover and broadcast information within the app about near by devices. Next, I was responsible for the map visualization. To accomplish this, I used Mapbox's Android SDK and integrated it with our various discovery services.
