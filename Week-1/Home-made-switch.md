## Project 1: Homemade switch

### TO MAKE:

An object with some LEDs that turns on and off with a homemade switch. It can be anything: sculptural, architectural, toy-like, stange, functional, useless. Try to use an unexpected material, and/or design an unexpected behavior.

Remember - a switch is just two pieces of conductive materials that touch together and come apart. Besides wire, try knives, coins, jewelry, silverware, tinfoil, springs... anything metal might work. And salty water! Design-wise, you can hide wires inside something else so it doesn't look "electrical".

Have fun! Play around, hack into stuff, experiment.

Write a blog post about your process and final result. Write down any questions as well! Questions are good.

### COMPONENTS:

We will distribute more components on Thursday. For now, you can find wires of various colors, resistors, and LEDs in the VFL supply closet and in our 3rd Floor Studio (Ask Rodel if you need anything specific). Additionally, you can get 9V battery connectors, more LEDs, electrical tape, and lots of other stuff locally at MicroCenter or online at [Sparkfun](https://www.sparkfun.com/?gclid=EAIaIQobChMIo82r5bSUgQMVw4poCR256ATwEAAYASAAEgKbJPD_BwE) or [Adafruit](https://www.adafruit.com/). If you're ordering parts online, remember to make time for shipping.

### HELPFUL TIPS:

You don't need to use the breadboard; it's probably easier to hide wiring without it, but either way make your wiring neat.

We didn't cover methods of attaching things yet, so you can just twist wires together, or use tape (electrical tape is best but duct tape works in a pinch), hot glue, or anything else that keeps the metal connection firm. Wrapping a wire around a screw and screwing into something with a piece of metal under it works well, if that's an option. Solid-core wire is easier to put in a breadboard but twisted/stranded wire is easier to braid together. There should be both kinds in the supply closet. (If you know how to solder already, great, go ahead.)

If you want to make something small, try coin cell batteries! [CR2032](https://tinkersphere.com/batteries-holders/528-cr2032-battery.html) is the standard, but any will work. You can tape wires to the battery but it will be more reliable if you use a holder. Here's a [single battery holder (3V)](https://tinkersphere.com/sewable-electronic-parts/425-sewable-cr2032-coin-cell-battery-holder.html), and here's a [double battery holder (6V)](https://tinkersphere.com/batteries-holders/1385-2-cr2032-coin-cell-battery-holder-with-onoff-switch-6v.html) You don't need conductive thread for the single sewable battery holder, any wire will work.

_Why would you use 6V vs 3V?_

To light up more LEDs! You don't need resistors for a single coin cell battery. If you use higher voltage batteries, you will. Don't forget to calculate resistance for your power source (3V, 6V, or 9V)!

#### RESOURCES:

Eample: [LED circuit with 9V battery](https://hellocircuits.com/2013/01/19/simple-led-circuit-with-9v-battery/)

- Note that it calls for a 350-470 ohm resistor, but a 220 ohm resistor with one LED will work (just will reduce its life a bit). 1k (1000) ohm resistor will work too although LED will be a bit dim. You can use a 3V coin battery if you want something small, with it you can get away with no resistor at all.

Practice Ohm's Law on your own, verify with this [calculator](http://ledcalculator.net/). NOTE: this shows the next highest common resistor value, not the exact calculation.

- Power Supply Voltage: your battery source (3V for a coin cell, 6V for two coin cells, 9V for a 9V battery, etc.)
- LED Voltage Drop: varies by color, click the "?" button to see numbers (doesn't need to be exact!)
- LED Current Rating: 20mA (average for most LEDs)
- Number of LEDs: up to you! (If your battery can handle it)
- Click the Design Circuit button first for wiring diagram, then select Schematic and click Design again (just to see what it looks like)

Here's a more in depth explanation of [using Ohm's Law with multiple LEDs](https://ericjformanteaching.wordpress.com/2017/09/15/ohms-law-and-seriesparallel/)

### INSPIRATIONS

Some projects from last year's students: [Sunwoo's blog](https://sunwoopark.notion.site/Week-1-A-Home-Made-Switch-fda4367647634878bc5af4a55d3342a2),
[Brenda's blog](https://brendason.notion.site/Homemade-Switch-f0e2a688aa274d07af95be87da1a4ae3),
