+++
date = '2020-09-01T00:00:00Z'
draft = false
title = "Distributed architecture for a smart LEDs display system based on MQTT"
tags = ["conference"]
# Only the publication month is known; the first day is used for chronological sorting.
+++

### Abstract
In the latest years, Light Emitting Diode (LED)-based lighting systems have revolutionarized architectural and design applications. The setup of a complex lighting system is a typically time-consuming task due to the number of manual operations that can it requires. In this paper, we introduce a LED-display system that aims at an automatic self-configuration while allowing a simple and effortless deployment. The proposed system is based on the careless deployment (in terms of positioning) of LED strips where each LED can be individually controlled and enlightened with the desired color. Since the position of every LED is not known during the deployment, we devised an automatic configuration procedure based on computer vision to determine the position of each LED, so that the LED can act as pixels to display a generic image. The different components of the system interact by exchanging messages with the Message Queue Telemetry Transport (MQTT) protocol. An example of application is provided that shows simple images displayed using the proposed display system.

### Useful links
Paper: [https://doi.org/10.1109/etfa46521.2020.9212084](https://doi.org/10.1109/etfa46521.2020.9212084)

### Bibtex

``` bibtex
@inproceedings{mqttleddisplay2020,
  author={Facchinetti, Tullio and Bonandin, Andrea and Benetti, Guido and De Martini, Daniele},
  title={Distributed architecture for a smart LEDs display system based on MQTT},
  year={2020},
  booktitle={2020 25th IEEE International Conference on Emerging Technologies and Factory Automation (ETFA)},
  pages={1243--1246},
  doi={10.1109/etfa46521.2020.9212084},
  url={https://doi.org/10.1109/etfa46521.2020.9212084},
}
```
