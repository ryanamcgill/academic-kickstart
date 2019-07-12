+++
# Date this page was created.
date = "2019-06-30"

# Project title.
title = "eMotes: Novel Disposable Airborne Probes"

# Project summary to display on homepage.
summary = "Deployable probes that take measurements from our atmosphere."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "/emote/emote.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["auburn"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).


+++

The National Oceanic and Atmospheric Association and GlobalSense partnered 
to sponsor the eMote in order to take measurements from the atmosphere. 
Data is streamed from an ensemble of sensors (up to 2080) to receivers 
located on the ground. 

<img src = "/img/emote/emote.png" width = "1000">

The system provides data on temperature, humidity, altitude, GPS, and 
inertial measurements from the atmosphere. The receiver's hardware consists 
of the Tiva-C Launchpad and TI-MSP430. TI-RTOS (Texas Instruments Real-Time 
Operating System) is used in order to wield excellent interrupt driven IO 
from the antenna. 

<img src = "/img/emote/system.png" width = "1000">

This project has been ongoing since I have been an undergraduate at Auburn. 
Currently I assist in testing the system, focussing primarily on the 
receiver end of the project. We most recently concluded range and battery 
testing. Future work consists of pulling wind vectors from the sensors as 
well as measuring resonant frequencies of static structures. 

<a href="https://file.scirp.org/pdf/WSN_2018072314435375.pdf">Project overview and image sources.</a>