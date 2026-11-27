# Schematic Source

Native Altium Designer schematic for the L298N motor driver board. The v1.1.0 schematic grounds both SENSE pins of U2 (pins 1 and 15); the original revision is preserved in the release/v1.0.0 branch.

## Initial source inspection

The component records identify an L298N motor driver, an L7805CV regulator, eight 1N4007 diodes, three polarized capacitors, an LED, a resistor and five headers. Net labels include VCC, +5, GND, EN1/EN2, IN1–IN4 and OUT1–OUT4.

This is an inventory-level inspection of the native source, not a full electrical rules check or a net-by-net verification. The SENSE return correction was checked in the native schematic and Altium ECO log. Remaining pin connectivity, component ratings and full ERC results have not been independently verified. Fabrication and functional testing were reported for the original revision only.
