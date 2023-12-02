# ICRS Line Following Robot Competition

### Sections:
* [Overview](#information)
* [Rules](#rules)
* [Date & Location](#date--location)
* [Getting Started](#getting-started)

<br>

![example-robot](/example-robot.png)

## Overview

The line following robot competition is an event held annually by ICRS where participants put their skills to the test by building and racing autonomous line following robots around a track, competing to get the fastest time.
[Example](https://www.youtube.com/watch?v=uSSDyEhkCK0)

This competition is great for people who’ve learned the basics e.g. from our [Robotics 101](https://github.com/ICRS/101) course.

## Rules

### The Robot
1) Line Followers must be self-contained, and not externally operated by wire or by remote radio control during the race.
2) Except for the battery pack, the handler shall not make any addition, removal, replacement or change to the hardware of a Line Follower during a contest. It is however permissible to make minor repairs.
3) A Line Follower shall not exceed 15 cm in overall length, 15 cm in overall width and 15 cm in overall height.

### The Track
1) The track is laid out using a black 20mm line on a white base.
2) The racetrack shall comprise of straight lines and circular arcs.
3) The radius of the arc shall normally be no less than 15cm (+/-5mm), measured from the centre of the line. The length of the arc shall be no less than 15cm.
4) Crossovers are permitted, but will be at right-angles only. Line Followers shall not turn left or right at a crossover.
5) A track may have arcs with different curvatures linked continuously.
6) The surface of the racetrack will be level.

![example-track](/track-example.png)

### Other
1) Robots will be judged on the time it takes to complete one lap, shortest time wins.
2) There will be time before the race for teams to test their robot's performance on the track at least 3-4 times.

These rules have been shamelessly stolen from [UKMARS](https://ukmars.org/contests/contest-rules/line-follower/).

## Date & Location
The 2023 competition will be held in EEE room 505 at 6pm on Friday 15th December.


## Getting started
If you participated in [Robotics 101](https://github.com/ICRS/101) you should hopefully have a working chassis that you can upgrade for this competition. If you didn't participate, then there are plenty of resources in the lab to make your own robot.

For following the line, we recommend using [IR sensors](https://circuitdigest.com/microcontroller-projects/interfacing-ir-sensor-module-with-arduino) which can be adjusted to give a digital output representing whether or not the line is under the sensor. Although if you have your own method of detecting the line that is completely fine too!

![IR-Sensor-Working](/IR-Sensor-Working.gif)

Good luck!