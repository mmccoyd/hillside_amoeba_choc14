# Readme

These are a single-switch PCB for choc Dactyl keyboards
  that allows choc 18 mm or narrower column spacing,
  sturdier column walls, and Mill-Max hot swap.
The main goal is
  to allow reusing the soldered up key matrix and MCU
  in a choc spaced key well
  when refining the key well shape after some real typing use.

See the wiki for [ordering]() details.

## Building

Currently using a build plugin in the toolbar.

## Size and fit

The PCBs are 13.7 x 16 mm.
That is as narrow as the bottom width of a choc switch,
  but provides a small lip at the top and bottom 
  to prevent removal of the switch from pulling the PCB out of the key well.
Small side notches help alignment with the switch socket.

## Panel layout

The panel spacing matches that seen in much of the key well.
This allows much of the wiring to be done before splitting
  the PCBs out of the panel.

A column separation of 20 mm
  adds 2 mm to the choc column separation
  as a bit of slack for the intervening key well wall.
This mirrors what is likely needed in the key well 
  for the often parallel pinky and index columns.

A row edge separation of 6 mm
  adds 2 mm to the key well 3.8 mm separation
  for a column of 16 mm PCBs with a 15 degree curve.
That separation leaves a decent tab between the PCBs
  to grip with pliers to break the PCBs cleanly apart.

## Design

Choc 18 mm spacing doesn't leave much space for switch supports
  between the columns of a Dactyl keyboard.
This amoeba takes up less width under the switch
  thus allowing the column side supports to extend below the switch body
  into where the PCB would normally be, reducing the support issue.

- The PCB extends past the switch hole top and bottom edges
  so the case will hold it down when a switch is pulled or pushed up to remove
  the switch.
- Column and Row solder holes are offset from the edge center
  to allow a switch puller to grip and pull closer to the edge center.
  Though I'm not sure this matters.

The narrow width eliminated the LED, and they would have
  made soldering more difficult.

## Other choc amoeba options

There are a few other choc Amoebas, though they have wider footprints:

- [Amoeba-choc](https://github.com/girishji/amoeba-choc)
  with monochrome LED and lower power draw, plus Kailh hotswap.
- [Nydas Amoeba](https://github.com/nydasco/nydas_keyboard_v2/tree/main/NydasAmoeba)
  with SK6812-mini-e LED and Kailh hotswap.
- [MxLEDBit](https://keycapsss.com/keyboard-parts/pcbs/173/mxledbit-single-switch-pcb-mx-choc-hot-swap-socket)
  with SK6812-mini-e LED and no hotswap.
- [Skree](https://www.skree.us) has MX spaced amoebas that also take choc switches.

## Status

- Amoeba likely fine, as is panel
- Build done with JLC button, not CI

## Next for Alpha-1




## Later

- Maybe flex link up the column, though it doesn't save much soldering

- Update: With socket STEP file for use in keywell design.
- Steal CI PCBA build from the MCU Corner project


## Design choices

### No allocated screw recess

There isn't much material under the top and bottom edges.
So recessing that edge for a screw leaves an unsupported screw hole.
