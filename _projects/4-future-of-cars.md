---
layout: project
title: Self-driving RC car
---

Self driving remote controlled car built from scratch with duct tape & soldering iron.

With RC car from Amazon, I put together a simple circuit on a breadboard to connect Raspberry Pi and car’s DC motors by soldering components together. 
After that, I made the car to be drivable from a simple web client, with camera and ultrasonic sensor streaming data.
Subsequently, I wrote a lane detection algorithm, then put a CNN in place that was learning from the camera feed, with overall learning process relying on a basic CML algorithm.

**Tech stack:**
- *python*
- *tornado*
- *tensorflow*
- *javascript*

[Source code](https://gitlab.com/futureofcars)

![_config.yml]({{ site.baseurl }}/images/futureofcars.png)

