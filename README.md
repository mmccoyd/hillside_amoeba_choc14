# Hillside Amoeba Choc14

|                 |                 |
|:-----------     |:----------------|
| ![Panel front](https://github.com/mmccoyd/hillside_amoeba_choc14/wiki/image/AmoebaPanel.front.png) | ![Amoeba Use](https://github.com/mmccoyd/hillside_amoeba_choc14/wiki/image/use_back.png) |

These are single-switch PCBs for Choc spaced Dactyl keyboards.

They allow Choc 18 mm or narrower column spacing,
  sturdier column walls, and Mill-Max hot swap.
Each has a PCBA SOD-123 diode, holes for a Choc v1 switch with optional
    Mill-Max sockets, and wire solder holes for creating the switch matrix.
The diode is from column anode+ to row cathode-.

Goals include
  allowing most of the matrix soldering to be done outside of the case
  and allowing reuse of the switches and matrix in a future case.

See the [wiki](https://github.com/mmccoyd/hillside_amoeba_choc14/wiki)
    for ordering details and wiring suggestions.
Their use is illustrated in the
    [Hillside Dactyl 50](https://github.com/mmccoyd/hillside_dactyl_50)
    wiki.

## Size and fit

The PCBs are 13.7 wide x 16 mm deep.

That is only as wide as the bottom of a choc switch,
  but adds a small top and bottom lip
  to prevent removal of the switch from pulling the PCB out of the key well.
Side notches serve to keep the top to bottom position aligned
  with the keyboard-body's switch-socket hole and to
  prevent the PCB from falling into the switch hole.

## Panel layout

The fabrication panel spacing matches that seen in a typical Dactyl key well.
That simplifies building by allowing much of the wiring to be done
  before splitting the PCBs out of the panel.

The column separation in the panel
  has a bit of slack for the intervening key well wall.
This mirrors what is likely needed in the key well 
  for the usually parallel pinkie and index columns.
The panel separation of 20 mm adds 2 mm to the choc 18 mm column separation.

The row edge-to-edge separation
    leaves a decent tab between the PCBs
    to grip with pliers to break the PCBs cleanly apart.
The separation of 6 mm adds 2 mm to the key well 3.8 mm separation
  for a column of 16 mm PCBs with a 15 degree curve.

## Version status

-   Alpha.4: Net yet tested. Has the larger SOD-123 diodes for hand soldering.
-   Alpha.3: Used without PCBA by A SadWitch. Has the small SOD-323 diodes.
-   Alpha.2: I used with PCBA for my Hillside Dactyl 50 alpha.2 and alpha.3.

## Images

Images of use in a build are in the
    [Hillside Dactyl 50](https://github.com/mmccoyd/hillside_dactyl_50) wiki.

![Use back](https://github.com/mmccoyd/hillside_amoeba_choc14/wiki/image/use_back.png)
![Panel front](https://github.com/mmccoyd/hillside_amoeba_choc14/wiki/image/AmoebaPanel.front.png)
![Panel back](https://github.com/mmccoyd/hillside_amoeba_choc14/wiki/image/AmoebaPanel.back.png)
![Schematic](https://github.com/mmccoyd/hillside_amoeba_choc14/wiki/image/amoeba_choc14.svg)

## Other Choc Amoeba options

There are a few other choc Amoebas, though they have wider footprints:

- [Amoeba-choc](https://github.com/girishji/amoeba-choc)
  with monochrome LED and lower power draw, plus Kailh hotswap.
- [Nydas Amoeba](https://github.com/nydasco/nydas_keyboard_v2/tree/main/NydasAmoeba)
  with SK6812-mini-e LED and Kailh hotswap.
- [MxLEDBit](https://keycapsss.com/keyboard-parts/pcbs/173/mxledbit-single-switch-pcb-mx-choc-hot-swap-socket)
  with SK6812-mini-e LED and no hotswap.
- [Skree](https://www.skree.us) has MX spaced amoebas that also take choc switches.
- [su120](https://github.com/kissetfall/su120-keyboard/tree/master)
