# Xbox Open Source Video Project - VGA
![Finished XOSVP Image](/images/enclosure.jpg)
XOSVP is an open-source alternative to the Microsoft HD AV Pack. The XOSVP strives to produce the absolute best analog video quality out of your original Xbox.

The VGA derivative you see here is an attempt to allow VGA connections between your modded Xbox and a VGA display. It will utilize a compatible pin-out to the original XOSVP-AVIP cable, with the addition of sync and a jumper. This will allow you to use one cable for either XOSVP or XOSVGA. Likewise, the board size will remain the same (hopefully), allowing the pre-existing case design to only require minor modification to allow for the additional DB-15 connector.
Currently, this design has not been tested, or even built, so do not expect it to work by any means. 

## Features
- Highest possible quality analog VGA video out
    - (tbd) Impedance matched board traces and cabling from original Xbox
    - High quality video filter + amplifier, [THS7316](https://www.ti.com/lit/ds/symlink/ths7316.pdf)
        - Low pass filter removes high-frequency noise and aberrations from the source signal without harming video frequencies
        - Reconstructs + Amplifies original signal to ensure matching with the VESA Standards (to check)
        - Reduces DAC Imaging effects on the video receiver
- Optical Audio/SPDIF
    - Best possible audio quality from the original Xbox
    - Support Stereo -> 5.1 Surround Sound
    - Cheap, high-quality optical DAC's easy to source on Amazon/Ebay for those without stereo systems

## More Details
[Check out the in-depth blog post on the original XOSVP detailing its construction, evolution, and comparison images.](https://blog.dtho.mp/2018/12/15/xosvp-intro/)

## Designs (original, to be updated)
- [**Schematics**](/xosvp.pdf)
- [**PCB**](/pcb.png)
- [**BOM**](/bom.csv)
- [**Enclosure**](/enclosure.obj)

All designs were produced with KiCAD 5. This includes all schematic sources, designed footprints, and PCB layout. VGA designs created in KiCAD 8.

## Enclosure (to be modified to fit 2nd DB-15 Connector)
![XOSVP Enclosure](/images/enclosure2.jpg)
Also within this repo is a 3D printable enclosure for the XOSVP. It is designed for friction fit so please ensure your 3D printer is calibrated properly before printing. All files were exported with Millimeter scale.

The enclosure was designed with Tinkercad, and you can view this design [HERE](https://www.tinkercad.com/things/6Rlx4JstT6S-xosvp-enclosure-v3).

## License
I want high-quality analog video from the original Xbox to be available to everyone, which is why I open sourced this project. Everything within this repo is covered by [CERN Open Hardware License v1.2](/LICENSE).

The VGA project has equal aims, and of course is covered by the same license.

## Contributing
If you have any suggested changes/improvements, please feel free to create an issue or a PR. They will be happily accepted!

I, the VGA designer, have limited experience with PCB design, so any input is greatly appreciated.

# Build Instructions
To Be Revised
