---
title: Reaction Wheels
layout: default
nav_data:
  - name: ADCS
    link: /github_pages/ADCS/
    repo: /oresat-acs-board
    defcolor: red
---
# CubeSAT-Reaction-Wheel

Portland State University is developing Oregon’s first orbital satellite, a 2U Cubesat dubbed Oresat. This cubesat will use a reaction wheel system for attitude control and pointing of the onboard antennas and cameras. I am developing the controller, designing the structure and sourcing hardware for both the space rated system and a ground test system that will also be used for demonstration purposes. This system has been tested using the Dryden Drop Tower at PSU as well as in captive hanging tests. The current controller is a simple proportional controller, however using data collected from the drop test I will refine the model and implement a more sophisticated controller. Video of the tests can be seen at:  [Captive Controller Hanging Test](https://www.youtube.com/watch?v=Is1gPHlewtgand) and [Dryden Drop Tower Micro-Gravity Test](https://www.youtube.com/watch?v=cC2FpmCP5B4)

Both of the previous tests were conducted using a simple open loop proportional controller that was tuned via test to induce a slightly underdamped response. This was to create data that can be more easily compared to an ideal model.

![CubeSat Model Comparison](https://github.com/oresat/reaction-wheels/blob/master/Modeling/Gyro_Data_vs_Model.png)

## Ongoing Development

There's a Google drive folder [here](https://drive.google.com/drive/folders/0BzW5XSZ87m-TVnFDZUc1TUkwN1U?usp=sharing)
