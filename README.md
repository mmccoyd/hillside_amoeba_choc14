# Readme

These are small single-switch PCBs for Choc spaced Dactyl keyboards.

They allow Choc 18 mm or narrower column spacing,
  sturdier column walls, and Mill-Max hot swap.
Each has a diode, Mill-Max socket holes, and oval solder holes
    for creating the switch matrix.
Goals include
  allowing most of the matrix soldering to be done outside of the case
  and allowing reuse of the switches and matrix in a future case.

See the [wiki](https://github.com/mmccoyd/hillside_amoeba_choc14/wiki)
    for ordering details and wiring suggestions.
Their use is illustrated in the
    [Hillside Dactyl 50](https://github.com/mmccoyd/hillside_dactyl_50)
    build notes.

## Size and fit

The PCBs are 13.7 wide x 16 mm deep.

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
  adds 2 mm to the choc 18 mm column separation
  as a bit of slack for the intervening key well wall.
This mirrors what is likely needed in the key well 
  for the usually parallel pinkie and index columns.

The row edge separation of 6 mm
  adds 2 mm to the key well 3.8 mm separation
  for a column of 16 mm PCBs with a 15 degree curve.
That separation leaves a decent tab between the PCBs
  to grip with pliers to break the PCBs cleanly apart.

## Status

-   Amoeba
    -   Seems fine.
    -   Alpha.2 was used to build Hillside Dactyl 50 alpha.2
    -   Smaller solder holes could be reasonable.
-   Panel
    -   Could use some silk and fiducial tweaks.
-   Build is currently done with a JLC button, not CI.

## Images

Images in a build are in the wiki.

![Panel back](https://github.com/mmccoyd/hillside_amoeba_choc15/wiki/image/panel_back.png)

## Other Choc Amoeba options

There are a few other choc Amoebas, though they have wider footprints:

- [Amoeba-choc](https://github.com/girishji/amoeba-choc)
  with monochrome LED and lower power draw, plus Kailh hotswap.
- [Nydas Amoeba](https://github.com/nydasco/nydas_keyboard_v2/tree/main/NydasAmoeba)
  with SK6812-mini-e LED and Kailh hotswap.
- [MxLEDBit](https://keycapsss.com/keyboard-parts/pcbs/173/mxledbit-single-switch-pcb-mx-choc-hot-swap-socket)
  with SK6812-mini-e LED and no hotswap.
- [Skree](https://www.skree.us) has MX spaced amoebas that also take choc switches.
