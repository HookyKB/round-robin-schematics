# ZMK Round robin with interrupt schematics

Just pluck the file you need. Probably best to copy and paste in to your kb schema.

Attach the global tags given to your controller on the pins you want to use and you're on your way.

The switches don't have an assigned footprint, so you'll need to assign your chosen switch to the schematic before updating your PCB view.

All diodes are set as 1N4148s and have the default footprint applied.

Individual switch diodes are labled as `D`, diodes for the switch return path as `DS` and diodes for the interrupt pin as `DI`.

The switches are labelled as `RC{driving_pin}-{driven_pin}` to help with the kscan/keymap setup once you've got your PCB layout sorted.
