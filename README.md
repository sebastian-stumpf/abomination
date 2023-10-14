# abomination

![abomination](abomination.jpg)

## Attention

I'm a hobbyist/amateur at best. So there may be things that aren't optimized. That being said I've had the files
in the `gerbers/` directory manufactured at JLC with 1.6mm thickness and they work just fine with my fork of the qmk repository
directory. So if you decide to use this, then please be advised that I'm not providing any sort of liability and you should
exercise some caution.

## Trackpad

The trackpad relies on the following adapter https://github.com/keyboard-magpie/minimal-fpc-i2c-pcb/ which can cheapily be PCBA'ed.
There reasons for using this adapter are that I hate soldering those tiny clamshell connectors and I can easily hot swap the
trackpad with an OLED display.

## Case

There are two plate versions for the case. The default version is very thin and wobbly and the switches aren't pressed in easily.
There's also a 'thick' version of the plates that sits on the pcb rock solid and the switches pop in with ease. I'd heavily recommend
the thick version. Just be aware that it will consume about 4 times the material as the thin plate.

## BOM

| Quantity   | Item                               | Comment                  |
| ---------  | ---------------------------------- | ------------------------ |
| 2          | Helios or Liatris Controller       |                          |
| 2          | IC-Sockets for MCU                 | Optional but recommended |
| 2          | TRRS Sockets                       |                          |
| 40         | 1N4148 SOD123 diodes               |                          |
| 2          | SKHLLBA010 buttons                 |                          |
| 36         | MX Hotswap Sockets                 |                          |
| 1          | EC12 Encoders                      |                          |
| 4          | 6mm tactile switches               | Longer caps work best    |
| 36         | MX Switches + Keycaps              |                          |
| 1          | Cirque 40mm curved trackpad        | Desolder R1 for i2c      |
| 1          | i2c adapter PCB for trackpad       | see above                |
| 1          | fpc cable for adapter              |                          |
| 1          | 4 pin dip socket and header        | for the adapter          |
| a lot      | M2 Screws (flat & countersunk)     |                          |
| also a lot | M2 heat inserts                    |                          |
| 12         | round bumpons with 3,1mm dia       |                          |


## Firmware

See [my fork](https://github.com/sebastian-stumpf/qmk_firmware/tree/sepp/keyboards/abomination) of the qmk repository. Nothing special here.
You can just copy the code over to your own repository and adjust the keymap.


## Feedback

I'm always happy to hear your opinions about this and if you decide to build this board then please do send me a picture of it.
