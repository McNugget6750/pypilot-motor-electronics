# pypilot-motor-electronics
Electronics for highly modified pypilot motor in my other repository

I spend the better part of a month to understand and rewrite major parts of the original pypilot motor controller code originally created by seandepagnier moderating the http://forum.openmarine.net/forumdisplay.php?fid=18 forum.

He did an amazing job pulling all these different software packages of OpenPlotter together and creating and maintaining the majority of them as far as I understand. However, the motor controller code needed some work and the controller hardware and h-bridge support needed polishing. I hope I was able to do both.

Design decisions:
* single sided
* hand assembly must be easy
* easy to understand schematics
* support for all sensors and switches originally supported by Sean's code
* additional display for debugging and state information
