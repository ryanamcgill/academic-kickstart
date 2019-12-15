+++
# Date this page was created.
date = "2019-09-11"

# Project title.
title = "QUEST: Quantum Encrypted Satellite-based Transmission"

# Project summary to display on homepage.
summary = "Nano-satellite to provide secure quantum communications."

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

As a project for the Department of Defense, QUEST aims to prove that secure 
communication can be realized via quantum key distribution from a ground 
station to a satellite. 

<img src = "/img/qkd/bb84.png" width = "1000">

I am contributing to the payload section of the satellite. In order to achieve 
quantum key distribution (QKD), the satellite's downlink beam must be aligned with the
ground station. Our payload is using the Bennet-Brassard 1984 scheme for polarization 
based QKD. Currently I am designing an embedded controller to take in camera data from 
the uplink and downlink beams and drive a fast steering mirror to achieve alignment. 

<a href="https://universitynanosat.org/">Link to University Nanosatellite Program </a> <a href="http://physique.unice.fr/sem6/2014-2015/PagesWeb/PT/Tomographie/?page=bb84">Image source.</a>