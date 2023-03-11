# minilabaen

![back of pcb](doc/pcb.png)

![keyboard layout showing what appears to be a 13u layout but 12.75u bottom row](doc/kle.png)

[kle](http://www.keyboard-layout-editor.com/#/gists/a9f61f5347eb8cae020ee2f3067dfd0b)


made in kicad 7.99 nightly

staggered layout with minibaen spacing (18.68mm x 19.05mm) except on bottom row, which is 12.75u 1.25/1/1.25/2.75/3/1.25/1/1.25 layout

based on minibaen r2, extraneous files from ortho minibaen have not been cleared out so uhhhh watch out.
edge cuts, usb port position, and some tray mount points are lifted from there

stm32f072 schematic is courtesy xphoenixd

this hasn't been tested. bom is missing LCSC info. don't use this.

## issues

* no good plate file, haven't gotten around to doing that yet. that svg in the plate folder is broken, and untested
* SW12 needs to be flipped to north facing, otherwise the pins interfere with usb
* some mount points found on other minivan pcb's are missing due to me being too lazy to re-place components and re-route, others interfere with switch footprints
* has not been tested at all

have fun!

zhol