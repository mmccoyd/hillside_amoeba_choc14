# Readme

This is a small single-switch PCB for Choc Dactyl keyboards.
It allows Choc 18 mm or narrower column spacing,
  sturdier column walls, and Mill-Max hot swap.
Its main goal is
  to support reusing the soldered up key matrix and MCU
  in a choc spaced key well
  when refining the key well shape after some real typing use.

Their use is shown in the [Hillside Dactyl 50]() build notes.

See the [wiki]() for ordering details and wiring suggestions.
Example use pictures from the Hillside Dactyl 50 build are
  also in this project's wiki.

## Size and fit

The PCBs are 13.7 x 16 mm.
That is only as wide as the bottom of a choc switch,
  but provides a small top and bottom lip 
  to prevent removal of the switch from pulling the PCB out of the key well.
Side notches serve to keep the top to bottom position aligned
  with the keyboard-body switch-socket hole and to
  prevent the PCB from falling into the switch hole.

## Panel layout

The panel spacing matches that seen in a typical Dactyl key well.
That simplifies building by allowing much of the wiring to be done
  before splitting the PCBs out of the panel.

The column separation of 20 mm
  adds 2 mm to the choc column separation
  as a bit of slack for the intervening key well wall.
This mirrors what is likely needed in the key well 
  for the usually parallel pinkie and index columns.

The row edge separation of 6 mm
  adds 2 mm to the key well 3.8 mm separation
  for a column of 16 mm PCBs with a 15 degree curve.
That separation leaves a decent tab between the PCBs
  to grip with pliers to break the PCBs cleanly apart.

## Other Choc Amoeba options

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

### Later (maybe)

- Maybe flex link up the column, though it doesn't save much soldering

- Update: With socket STEP file for use in keywell design.
- Steal CI PCBA build from the MCU shield project

