<p align="center">
    <img src="assets/JEL05570.jpg" style="align:centre" width="50%">
</p>


The Dingo is a low-cost robotic quadruped built using 35kg servo motors.

This was completed for a University Capstone Project by Nathan Ferguson and Alexander Calvert

Code and Bill Of Materials:
https://github.com/Yerbert/DingoQuadruped

Video:
https://youtu.be/8KntOIgzUjY

<p align="center">
    <img src="assets/JEL05546.jpg" style="align:centre" width="50%">
</p>

Some build notes:
- The black piece which acts to transfer the motion of the lower servo to the lower leg should be printed in two parts, then have a bearing inserted, then be glued together. There are configurations in Solidworks to allow the export of this but I will try add all STLs soon.
- All parts in contact with the motors MUST be printed in ABS for temperature resistance. PLA parts will soften due to the heat the motors produce (although this may be avoided using the fans). So all orange parts are ABS as well as the black hub which holds the servos for the upper and lower leg. Note that the upper leg is in contact with the servos via the bolts which attach it so should also ideally be printed in ABS to avoid any issues.
- The rear upper and lower parts (large orange parts) that go aroudn the ports of the PI should be printed as a single piece. They were designed separate but you will get much better results just exporting the sub assembly as an STL and printing that
- All heat set inserts should be pushed in with a soldering iron tip. See here https://www.youtube.com/watch?v=hwq15qH-4x4
-
UPDATE: STEP file has now been added. STLs to come.


Special thanks to the open-source designs that helped inspire aspects of this project:
- Stanford Pupper V1: https://pupper.readthedocs.io/en/latest/index.html
- Stanford Pupper V2: https://pupper-independent-study.readthedocs.io/en/latest/
- Notspot: https://github.com/lnotspotl/notspot_sim_py
- Kangal: Diy quadruped robot
- SpotMicro: https://www.thingiverse.com/thing:3445283, https://spot-mini-mini.readthedocs.io/en/latest/index.html
- Nova SM3: https://novaspotmicro.com/
- Mini Pupper: https://minipupperdocs.readthedocs.io/en/latest/guide/Features.html
