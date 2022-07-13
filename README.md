# RF Generator
500W RF generator, tuned for 13.56MHz
Based on the paper [1kW Wideband Class E Power Amplifier](https://superlab.stanford.edu/publication/kw_mhz_wideband_class_e_power_amplifier_jiale/) from the Stanford Superlab.

I removed the duplicate circuit (for simplicity), added a FET driver, clock, and Arduino for control.

![Front view of PCBA](https://github.com/kamocat/rf_gen/blob/main/front_view.png "Front View")

## Cost breakdown
| Category | Price | Description |
| --- | --- | --- |
| Assemblies | 19.95 | Arduino & Si5351 |
| Components | 47.25 | Parts that get soldered on |
| Consumables | 33.94 | Solder and magnet wire |
| Hardware | 4.89 | Screws, heatsink, thermal interface pad |
| PCB | 30.00 | From OSH Park. 2 oz copper |


## Electrical simulation
Simulation is done with LTSpice.
You will need the spice models for the [SiC mosfet](https://www.genesicsemi.com/sic-mosfet/G3R30MT12J/G3R30MT12J_SPICE.zip) and the [GaN mosfet](https://gansystems.com/wp-content/uploads/2020/02/GS61004B-Spice-Models-V4P2.zip)

## Thermal simulation
Simulation is done with Elmer / FreeCAD. Work in progress...
