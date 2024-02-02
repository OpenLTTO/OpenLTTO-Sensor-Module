# OpenLTTO
The OpenLTTO Project is an attempt to recreate the Lazer Tag Team Ops protocol, and game system, in a completely open-source solution. Eventually our intent, is to expand on the LTTO system, adding new functionality, and features, while maintaining backwards compatibility with this classic Lazer Tag gear.

> This Project wouldn't be possible without all the hard work of Richie Mickan https://github.com/rmick
> His work on recreating the LTTO Protocol, and the development of the Combobulator app are core to the firmware and capabilities of this project.

> Additionally this is built on top of the excellent product developed and released by Hasbro/Tiger Electronics. And the work done by Tag Ferret to release the technical specs, and unlock much of the magic of the protocol, and the inner workings.

We intend to do this via a collection of open-source hardware components that can act as building blocks, to build anything you might require for a Lazer Tag game (Taggers, Hosting Pods, Zone controllers, utilities, etc). And an opensource firmware to operate it all. 

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

# OpenLTTO Sensor Module
The OpenLTTO Sensor Module is designed to act as either a sensor dome on a Tagger, or a sensor dome on a "Hosting Station" (such as for use with Combobulator), or within a utility component (Zones, Grenades, or any other component you can think of that needs to use 360 degree IR).

It is designed to be paired with a 50mm clear dome, and encased in a 3D Printed "Sensor Module" chassis which can then be embedded in other projects such as Taggers etc.

The module includes 5 Pin IR IN and IR OUT ports, and 4x pairs of IR Transmitter and IR Receiver. The transmitters are more wide angle (TSAL6400) compared to the barrel module, and with this arrangement should provide effective 360 degree coverage. The circuit includes an optimized 1A LED Driver for each IR LED, ensuring full current output per LED. The Module supports both outdoor (high power, 1A), and indoor (low power) modes, controlled from the motherboard. And includes a 2x power ballasts (capacitor, and inrush arrester pair) to prevent ripples, and ensure smooth operation.

## OpenLTTO Sensor Module Top Side
![Image of OpenLTTO Sensor Module Top](https://github.com/OpenLTTO/OpenLTTO-Sensor-Module/blob/main/OpenLTTO%20Sensor%20Module%20Top.png?raw=true)

## OpenLTTO Sensor Module Bottom Side
![Image of OpenLTTO Sensor Module Bottom](https://github.com/OpenLTTO/OpenLTTO-Sensor-Module/blob/main/OpenLTTO%20Sensor%20Module%20Bottom.png?raw=true)
