# Planetary Gear Kinetic Extruder Visualizer

https://www.thingiverse.com/thing:4192890

Customizable, planetary gear, kinetic extruder visualizer.

Derived from Emmett's gear bearing, which is designed as print-in-place to be locked together with herringbone gear teeth. But this visualizer is so thin (4mm) that it doesn't hold itself together, it can be assembled after printing. So it's easy to print the parts in different colors.

The ring gear is held in place by 4 circular tabs that press fit into the screw holes of standard NEMA 17 stepper motors.

The hexagonal center rod requires an **8mm** diameter by **3mm** tall neodymium magnet to hold itself to the stepper motor shaft. Glue the magnet to the hex shaft with super glue.

Slide the hex shaft into the sun gear. Adjust the position of the sun gear on the hex shaft so that the sun gear rides in the same plane as the planet and ring gears.

This print does not like tight tolerances. The magnet can't transfer much torque from the motor shaft, and if the gears stick at all then they won't turn. For me 0.3 mm tolerance let the gears move freely without binding. 0.2 was too tight and 0.5 mm tolerance couldn't hold itself together, I didn't try 0.4 mm.

## Print settings

- 1 Perimeter
- 2 Bottom layers
- 3 Top layers
- 0% Infill

Ring gear:

- 2 Perimeters

Optional settings for ultra lightweight, hollow gears:

- 0 Bottom layers
- 0 Top layers
- 20% Infill for sun gear, honeycomb pattern
