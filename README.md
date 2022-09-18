# CurrentTrigger

## Description
This circuit will detect a current flowing through a current mirror and outputting a low-level signal once it reaces a certain threshold.
This is intended to work as a controller detection circuit for various consoles in combination with [DarthCloud](https://github.com/darthcloud)s [BlueRetro](https://github.com/darthcloud/BlueRetro) adapters for internal installation.

## Idle Currents per Console

| Controller | Idle Current |
|-|-|
| N64 (OEM) | 6 mA |
| DS2 (OEM) | 8 mA |
| GC (OEM) | 7.5 mA|
| MegaDrive (OEM)| <1 µA|
| NES (OEM) | <1 µA |

The circuit is designed to reliably output a low-level at a threshold of 300µA! Any controller consuming less in idle state is not detectable.

## Exampe Installation Points

- To be written

## Implemenatations using this approach
GameCube BlueRetro Internal Adapter by Collingall/Laser Bear Industries [Link](https://www.laserbear.net/products/gamecube-blue-retro-internal-adapter)
