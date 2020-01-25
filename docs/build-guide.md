# Arc Lamp Build Guide

<img src="/img/build00-00.jpg" alt="build00-00.jpg" width="600">

Design reverse engineered from the original [Heng Balance Lamp on Kickstarter](https://www.kickstarter.com/projects/1458079400/heng-balance-lamp-a-unique-lamp-with-switch-in-mid)

Laser cut design based on original files by [JustAddSharks on Instructables](https://www.instructables.com/id/DIY-Heng-Lamp/ )

---
### Table of Contents
* [Materials](#Materials)
* [Laser Cut Parts](#Laser-Cut-Parts)
* [Build Lamp Base](#Build-Lamp-Base)
---

## Materials
See [Bill of Materials](https://docs.google.com/spreadsheets/d/1lHaNQ_by_0eQF1vNenDIT_l0-mevZIj3L4IccVn72g8/edit#gid=0) for parts to purchase

Other materials needed include:
* Wood Glue
* Paper Towels
* 4 to 8 mini wood clamps
* Sandpaper (80 and 120 grit)
* 1" wide Painters Tape
* 22 AWG Solid Core wire in Red, Black, White
* Hot Glue Gun
* Soldering Iron

## Laser Cut Parts
See Adobe Illustrator file [`arc-lamp-laser-cut.ai`](\hardware\mech\arc-lamp-laser-cut.ai)

The file organizes material type by Layers.

* ¼” parts take about 20 min
* ⅛” parts take about 10 min

  <img src="/img/build01-01.jpg" alt="build01-01.jpg" width="600">

  <img src="/img/build01-02.jpg" alt="build01-02.jpg" width="600">

## Glue Laser Cut Stack-ups
### Glue Bottom Base Stack-up
* Apply wood glue to both sides of **Base 2**
* Stack and clamp **Base 1**, **Base 2**, and **Base 3** (sets in about 5 min)

  <img src="/img/build02-01.jpg" alt="build02-01.jpg" width="300">
  <img src="/img/build02-02.jpg" alt="build02-02.jpg" width="300">

* Fill base with BBs to add weight

  <img src="/img/build02-03.jpg" alt="build02-03.jpg" width="300">

* Apply wood glue to top of **Base 3**
* Stack and clamp **Base 4** to seal BBs in base (sets in about 5 min)

  <img src="/img/build02-04.jpg" alt="build02-04.jpg" width="300">


### Glue Mid Base Stack-up
* Stack Mid 1 to 3 with wood glue. Clamp for 5 min until set.
* Stack Mid 5 to 7 with wood glue. Clamp for 5 min until set.
* Sandwich Mid 4 between the previous 2 stacks with wood glue. Clamp for 5 min until set.

### Glue Arc Stack-up
* Flip Arc 1 so the “clean side” is facing out. Stack Arc 1 and Arc 2 with wood glue. Clamp for 5 min until set
  * **Note**: Align the _outer edges_. There is an intentional lip along the inner edges.
  * Carefully wipe away excess glue along the inner edges to make them as smooth as possible. We will sand the outer edges for smoothness, but the inner edges are more difficult to sand.

* Flip Arc 7 so the “clean side” is facing out. Stack Arc 6 and Arc 7 with wood glue. Clamp for 5 min until set
  * **Note**: Align the _outer edges_. There is an intentional lip along the inner edges.
  * Carefully wipe away excess glue along the inner edges to make them as smooth as possible. We will sand the outer edges for smoothness, but the inner edges are more difficult to sand.

* Stack Arc 3 to 5 with a generous amount of wood glue between them to allow it to stay “wet” longer.
* Add the Arc 1+2 and Arc 6+7 stacks to either side of the Arc 3,4,5 stack with wood glue.
* Align and clamp the entire arc stack together for 10 min until set.
* When dry, the outer edge of the Arc stack may be slightly offset and/or have some excess glue dried along the edge. We will even this out by sanding it down later.

### Glue Top Base Stack-up
* Stack Top 1-B to 3-B with wood glue. Clamp for 5 min until set.
* Insert [0.5 x 0.25 Ring Magnet](https://www.kjmagnetics.com/proddetail.asp?prod=R841) into cavity of Top 3-B.
* Stack Top 4-B on 3-B with wood glue to capture magnet. Clamp for 5 min until set.
* Stack Top 1-A to 4-A with wood glue. Clamp for 5 min until set.
* Stack Top 1-C to 4-C with wood glue. Clamp for 5 min until set.

### Combine Mid and Top Stack-up
* Ensure top of layer Mid 7 is flat (no bumps from dried glue) - sand down if necessary.
* Place the Arc stack on top of the Mid stack. Be very careful to align the arc face with the power jack and fader placement on the Mid stack.
* Apply wood glue to the top of the Mid stack along the area outside of the Arc stack (where the Top-A and Top-C stacks will be going).
* Carefully place the Top-A and Top-C stacks on top of the Mid stack on either side of the Arc stack. Be sure to align the outer edges of the Top and Mid stacks and maintain the parallel tracks for the Arc stack. Do not clamp - clamping will likely misalign the stacks. Simply wait about 10 min for wood glue to dry.
* **Note**: Do not glue Top-B Stack yet. This will happen after electronics are installed.

## Drill, Sand, and Finish Wood
* Using drill press, drill 1/2” hole for the power jack in Base
* Using drill press widen 5/16” hole for potentiometer in Base
* Sand all exterior surfaces of base, mid, top and arc. Power sander to start, manual sanding to finish.
  * **Note**: This is not a trivial step - budget about 2 hours for sanding
  * Rough sand the Arc edges on the Horizontal Belt Sander
  * Rough sand the Base on the Vertical Belt Sander
  * Sand the Arc faces and final Top piece with a Hand Power Sander
  * Manually finish sand all pieces with 120 grit sand paper. Pay special attention to rounding the corners of the Arc.

* After sanding, wipe down all pieces with a damp paper towel to remove dust. Let wood dry for 10 min.
* _Optional_: After wood is dry, rub exterior surfaces with mineral oil to accentuate the wood grain.

## Install Electronics
#### LED Strip
* Cut length of 29.75” LED strip
* Cut bits of silicone sheath from either end and solder 6” lengths of 22 AWG solid core wire to both ends. Reinforce solder joints with hot glue.
  * (2) Black - LED GND
  * (2) White - LED PWR
* Cut silicone sheath away from exact center (14.875"). Ball capture will be placed here later.
* Super Glue 1/16” thick acrylic string capture base piece (larger hole) into center of LED strip.
* Insert LED strip into Arc. Start by placing center cutout at Arc exact center and fit LEDs into Arc from center to either end.
* Reinforce interface of LED sheath and Arc on either side of central string capture with hot glue to prevent LEDs from pulling away from arc body.

#### Dimmer Potentiometer
* Remove Potentiometer from enclosure. Desolder connector socket from dimmer PCB. Replace with 6” lengths of 22 AWG solid core wire. Reinforce solder joints with hot glue.
  * (2) Black - LED GND
  * (2) White - LED PWR
  * (1) Red - Vin 12V
  * (1) Black - Vin GND
* Solder 6” of Red 22 AWG solid core wire to the C and  NO contacts on the limit switch. Reinforce solder joints with hot glue.
* Solder 6” lengths of 22 AWG solid core wire to Power Jack. Reinforce / isolate solder joints with hot glue.
  * (1) Black - Vin GND (leaf pin)
  * (1) Red - Vin 12V (center pin)

* Install limit switch into fixture on Arc stack. Tighten nuts. Hot glue switch terminals and nuts in place.
* Insert Power jack into  Mid stack. Screw on Hex Nut. Cover terminals in Hot Glue.
* Install Pot with wires facing "up", secure dimmer PCB with Hot glue.

## Install Diffuser Strip
* Cut (2) lengths of diffuser strip 24” x 23 mm (width is very precise)
* Fit strips around inner Arc, meeting at the center of the LED strip

[... in progress ...](https://photos.google.com/u/1/album/AF1QipPvCgZ2smGo4TUfmTWPi4l-RyJBR18gE8JOZjN9)
