MindCub3r v2p2
==============

MindCub3r LEGO MINDSTORMS robots can solve the well known Rubik's Cube puzzle.

There are two EV3 variants that can be built from either a single LEGO
MINDSTORMS EV3 set (item 31313, home edition) or from a combination of the
LEGO MINDSTORMS EV3 Education Core and Expansion sets (items 45544 and 45560)

Construct the robot by carefully following the build instructions and then
download and install the software as described on the MindCuber website:

http://mindcuber.com/mindcub3r/mindcub3r.html

Share your experiences and help others with troubleshooting tips on the
MindCuber facebook page:

https://www.facebook.com/lego.mindcuber

Copyright (C) 2013-2019 David Gilday

Change history:
--------------

v2p2  + add support for medium motor using port D instead of port C

v2p1  + improve scan reliability by changing detection of "bright" cubes

v2p0  + make compatible with older firmware versions such as 1.06H

v1p9  + add scramble pattern option

v1p8  + improve calculation time for some cube positions
      + improve auto white balance for red/orange discrimination
      + adjust scan speed and position
      + use adaptive delay for color sensor in RGB mode

v1p7  + improved auto white balance (particularly for bright orange)
      + reduce threshold to improve scan position with low battery
      + adjust position of scan arm for edge pieces to improve scan
      + increase range for IR sensor for more reliable cube detection

v1p6  + improve solve algorithm (still small enough for Education firmware)
      + only resolve "cube errors" on third scan

v1p5  + automatically adjust scan sample position to improve scan reliability

v1p4  + adjust scan speed and position
      + rescan face on color sensor error
      + use information from multiple scans to attempt to resolve scan errors

v1p3  + ability to solve directly to patterns selected using EV3 brick buttons
      + timer and progress information during solve
      + move cutting to improve reliability with stiffer cubes
      + faster, more reliable scan
      + adjusted tilt motion to improve reliability
      + reduced size of mc3solver executable program
      + support for variant built from EV3 Education Core and Expansion sets

v1p2  + (not released)

v1p1a + support for standard LEGO firmware using brick app

v1p1  + rename autorun and mc3solver executable to support download on Mac
      + improved scan (with modified scan arm)
      + scan retries 3 times after error
      + turntable adjustment using EV3 brick buttons

v1p0  + initial release

*END*
