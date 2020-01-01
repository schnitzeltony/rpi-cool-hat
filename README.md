# rpi-cool-hat

* At least Raspberry Pi 4 makes additional cooling mandatory.
* Most cooling solutions (all but oil?) do not allow stacked HATs (and at least musicians do not accept builtin audio).

This KiCad project suggests a glue-PCB letting coolers and HATs live in peace:

![3d-preview](https://user-images.githubusercontent.com/2571823/71328625-89d47100-251a-11ea-8788-3c4cf56e014f.png)

RPi is connected right / HAT connected left (upside-down) / cooler's fan connected to pins in the back.

Note that project:

* was created by Kicad 5.1.5 as shipped by Fedora 30
* is in early stage: Nothing soldered / no tests performed yet
* 's author is not a profesional layouter - awaiting PRs/issues - teach me :grin:

If you want one:

* drop [rpi-cool-hat.kicad_pcb](rpi-cool-hat.kicad_pcb) to a supplier of your choice
* if your supplier does not accept Kicad: clone this project, go through gerber and send that to your supplier.
  To get an idea of how to accomplish it might help to watch https://www.youtube.com/watch?v=ENmDnoKs2hM
* or visit https://aisler.net/p/IRBRWUAC. Note that the author has no relation to Aisler.
  It was chosen because their production was considered close at time and place of writing.
