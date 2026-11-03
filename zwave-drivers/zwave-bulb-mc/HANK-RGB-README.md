# Z-Wave Bulb Mc (Hank RGB)

This is a lightly modified copy of **Z-Wave Bulb Mc**, the SmartThings Edge driver written by **Mariano Colmenarejo** ([Mariano-Github/Edge-Drivers-Beta](https://github.com/Mariano-Github/Edge-Drivers-Beta)). All credit for the driver goes to him. It is licensed under the Apache License 2.0, and the original copyright notices are kept.

## Changes from the original

- zwave-bulb-mc-v2/fingerprints.yml: added the Hank HKZW-RGB01 RGB bulb (also sold as the Monoprice Z-Wave RGB bulb), fingerprint 0208/0101/0004, using the rgbw-bulb profile so it gets color control.
- zwave-bulb-mc-v2/config.yml: renamed the package to "Z-Wave Bulb Mc (Hank RGB)" with its own package key so it does not clash with the original.

No driver code was changed.
