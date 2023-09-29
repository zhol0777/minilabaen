# minilabaen

![back of pcb](doc/pcb.png)

![keyboard layout showing what appears to be a 13u layout but 12.75u bottom row](doc/kle.png)

[kle](http://www.keyboard-layout-editor.com/#/gists/a9f61f5347eb8cae020ee2f3067dfd0b)


made in kicad 7.99 nightly, sorry

staggered layout with minibaen spacing (18.68mm x 19.05mm) on the top two rows (to handle keysets with boycott kitting)
19.05mm x 19.05mm spacing on the bottom alpha row, and modifier key row
modifier key row supports 1.25/1/1.25/2.75/3/1.25/1/1.25 layout for spacebar kits designed by people who included only a single 3u bar, and jetvan

based on minibaen r2, extraneous files from ortho minibaen have not been cleared out so uhhhh watch out.
edge cuts, usb port position, and some tray mount points are lifted from there.

gerbers and dxf for plates for tray mount and coriander top mount are provided.

pcb prototype was confirmed functional as of sept. 27, 2023. plates are awaiting prototyping still.
the firmware source needs some fixes and updates, will provide those shortly.

## thanks

* stm32f072 schematic is courtesy xphoenixd
* kiser for suggesting leaving normal spacing on bottom alpha row
* rain on basic tips on how to generate plate files easily, as well as part number for ESD chip
  * islandworks, matt, and mel for suggesting I don't use "ballsack" ESD chip 

## issues

* SW12 needs to be flipped to north facing, otherwise the pins interfere with usb. if you intend on using this in tray mount, you may need to clip the switch legs.
* SW43 needs to be flipped to north facing, to prevent interference with bottom right tray mount point.
* some mount points are excluded due to interference with components or switches
  * one of the mount points on the 3U bar cannot be screwed in since it is in the same location as the 3u stabilizer. the best way to deal with this is to use GMK 3U bars, which contain stems for 2U stabilizers as well.

have fun!

zhol
