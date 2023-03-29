# minilabaen

![back of pcb](doc/pcb.png)

![keyboard layout showing what appears to be a 13u layout but 12.75u bottom row](doc/kle.png)

[kle](http://www.keyboard-layout-editor.com/#/gists/a9f61f5347eb8cae020ee2f3067dfd0b)


made in kicad 7.99 nightly

staggered layout with minibaen spacing (18.68mm x 19.05mm) except on bottom row, which is 12.75u 1.25/1/1.25/2.75/3/1.25/1/1.25 layout for spacebar kits designed by people who included only a single 3u bar (usually the same people who exclude van backspace, or china kitting or something)

based on minibaen r2, extraneous files from ortho minibaen have not been cleared out so uhhhh watch out.
edge cuts, usb port position, and some tray mount points are lifted from there

stm32f072 schematic is courtesy xphoenixd

this hasn't been tested. don't use this.

## issues

* SW12 needs to be flipped to north facing, otherwise the pins interfere with usb
* some mount points are excluded due to interference with components or switches
  * one of the mount points on the 3U bar cannot be screwed in since it is in the same location as the 3u stabilizer. the best way to deal with this is to use GMK 3U bars, which contain stems for 2U stabilizers as well.
* has not been tested at all. mounting holes and usb port may be slightly off. hopefully the tray mount plate is fine

have fun!

zhol