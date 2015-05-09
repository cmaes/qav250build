# QAV 250 Build Information

## Materials

1. [QAV 250 G10 frame](http://www.getfpv.com/multi-rotor-frames/mini-multi-rotor-store/mini-multi-rotors/qav250-mini-fpv-quadcopter.html)

2. [Naze 32 flight controller](http://www.getfpv.com/flight-controllers/acro-naze32-flight-controller-straight-right-angle.html)

3. [FrSky Taranis Radio and X8R receiver](http://www.getfpv.com/radios/radio-controllers/frsky-taranis-x9d-plus-2-4ghz-accst-radio-x8r-combo-w-case-mode-2.html)

4. [Lumenier CS 600 Super 600 camera](http://www.getfpv.com/lumenier-cs-600-super-600tvl-d-wdr-camera-no-case.html)

5. [Immersion RC 600mW Video Transmitter](http://www.getfpv.com/5-8ghz-600mw-video-tx.html)

6. [FXC1806-14 2300kv Motors](http://www.getfpv.com/multi-rotor-frames/mini-multi-rotor-store/mini-motors/fxc1806-14-2300kv.html)

7. [Simon K Blue Quadcopter Esc 12A with BEC for Mini Quads](http://quadquestions.com/product/simon-k-blue-escs-12a/)

## Data sheets

* [Naze 32](http://www.abusemark.com/downloads/naze32_rev3.pdf)
* [Super 600 camera](http://www.getfpv.com/media/manuals/2040_osd_menu_manual.pdf)
* [X8R receiver]

## Configuration software

* [Naze 32](https://chrome.google.com/webstore/detail/baseflight-configurator/mppkgnedeapfejgfimkdoninnofofigk?hl=en)

## Build steps

Follow the QAV 250 G10
[manual](http://www.lumenier.com/products/multirotors/qav250/build-manual)

for steps 1 - 3

1. Solder the underframe LEDs to the power distribution board

   24 gauge flexible wire

   [LED connection](https://youtu.be/OHPvexW6zpg?t=357)

   Use corner connection for LEDs

2. Solder the XT60 power connector to the power distribution board

   Use back pads for power connections

   https://youtu.be/OHPvexW6zpg?t=453

3. Solder the ESCs to the power distribution board

   Solder: 62/36/2 silver rosin core electrical solder

   Pretin PDB and ESC leads

   [Soldering ESCs](https://youtu.be/OHPvexW6zpg?t=90)

   Be mindful of standoff holes

4. Solder voltage supply (in middle side) for NAZE 32 to PDB

5. Solder voltage supply for FPV gear to PDB (removable clip on end)

6. [Wrap ESC controls around ferrite bead](https://youtu.be/OHPvexW6zpg?t=577)

7. Label ESCs on PDB and ends of ESC control wires

8. [Add spacers (standoffs for NAZE 32)](https://youtu.be/OHPvexW6zpg?t=586)

9. Solder header pins for the ESCs onto the NAZE 32 board

10. Solder header pins for receiver channels on NAZE 32

11. Solder power and gnd header to Naze 32

12. Attach ESC and power and gnd underneath NAZE board

    https://youtu.be/OHPvexW6zpg?t=735

13. Solder wires from channels 1-4 (6?) from X8R to NAZE 32 board

14. Attach Naze 32 to stand offs on drone


15. [Use the self-tapping screws to attach the LEDs to the underside of the frame](https://youtu.be/OHPvexW6zpg?t=993)

   Recess for LEDS are on the bottom

   Pretin LED board

   Note that yellow LEDs (white lights) go at the front and white LEDs (red lights) go at the back

   Electrical tape on back of LED board (necessary for G10 frame or only for carbon fiber?)

   [Tapping screws](https://youtu.be/OHPvexW6zpg?t=1071) be careful, go in slowly, back out, and go in again, and come out again

16. Tighten PDB screws and add blue lock tite

17. Add landing gear

18. Mount the motors to the frame using lock tite for screws

19. Solder the motors to the ESCs making sure that two motors turn clockwise and two turn counter clockwise.

    [Directions picture](https://youtu.be/OHPvexW6zpg?t=2010)
    CW   CCW
    CCW   CW

    [Don't shrink shrink wrap until test the rotation](https://youtu.be/OHPvexW6zpg?t=1221)

    Crossing two wires will flip motor direction

    Put shrink wrap over bare connections between ESCs and motors to avoid shorts

20. Flash firmware on NAZE 32 if necessary

    Connect NAZE 32 to USB

    [Configuration](https://youtu.be/OHPvexW6zpg?t=1335)

21. Verify NAZE is in proper configuration by moving drone and watching movement
    on configuration display

21. Get ready to power on drone and test motor/NAZE configuration

    Go to motor testing tab

    Click check in motor test mode notice

    [Loosley connect battery](https://youtu.be/OHPvexW6zpg?t=1481)

    Look for shorts, disconnect if any magic smoke

22. Check motors and directions and reverse direction if necessary

23. Continue on to FPV. Solder connection from PDB to Immersion RC receiver

24. Cut camera down to fit into drone

25. Solder connection between camera and Immersion RC

26. Set failsafes on NAZE to off

27. Attach props (making sure that props are in correct direction). CW props on CW motors
    5 X 3  and  5 x 3 R for different rotations?
