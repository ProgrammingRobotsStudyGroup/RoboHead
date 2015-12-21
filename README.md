# RoboHead
Robot head and control panel.
The idea is that this can act both as a part of the robot or be removable. While this could/should talk to ROS master, it probably shouldn't be a master.

## (Potential) Objectives
* Displays a face which can talk, etc. This need not mimic humans.
* Speech synthesis (talk, sing, etc.)
* Sound generation
* Speech recognition
* Diagnostics and status panels
* Integrate with ROS

## Technology stack
# WebPage: UI representation container.
* Web Sockets: Facilitates communication most particularly push
* CSS3 Animation: Implements the underlying animation

## Why this approach?
The HTML development community is large. Hosting a head on a web page makes sharing an implementation a simple matter.
Finally, this means using a new head or any other representation is installationless.

A web hosted head can be viewed and exercised with a browser. While we intend to use an Android app to implement this, 
others may elect to use a screen on a laptop or connected to the Pi.

Thinking further ahead, this approach does not limit the visualization to just a head. It might be fun to watch a wag tail.
