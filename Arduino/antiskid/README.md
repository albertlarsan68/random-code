# Antiskid

This program detects when there is too much difference between front wheel and back wheel rotations.

## Schematic

![Schematic](docs/Schematic.svg)

## Compatibility

This code is compatible with any Arduino or compatible board, that meets the following requierements:

- Interrupt on pins 2 and 3, with `FALLING` detection
- `INPUT_PULLUP` mode on pins 2, 3, 4
- `OUTPUT` mode with PWM on pins 5, 6, 9

The Uno and Nano Every boards are tested to be compatible, but any feedback is welcome.