# rpi-cool-hat

* At least Raspberry Pi 4 makes additional cooling mandatory.
* Most cooling solutions (all but oil?) do not allow stacked HATs (and at least musicians do not accept builtin audio).

This KiCad project suggests a glue-PCB letting coolers and HATs live in peace:

![3d-preview](https://user-images.githubusercontent.com/2571823/74680400-ccd05f00-51c0-11ea-8b42-30c72e02016b.png)

RPi is connected left / HAT connected right / cooler's fan connected to pins in the back as (example pictures are 180°rotated):

![real-life](https://user-images.githubusercontent.com/2571823/75122543-cc433700-569e-11ea-84d6-d1d8f1d4ed08.JPG)


**Note that the project:**

* was created by Kicad 5.1.5 as shipped by Fedora 30
* 's author is not a professional layouter - awaiting PRs/issues - teach me :grin:
* was tested with HifiBerry DAC Pro and Flatmax AudioInjector
* IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND!

**If you want one:**

* drop [rpi-cool-hat.kicad_pcb](rpi-cool-hat.kicad_pcb) to a supplier of your choice
* if your supplier does not accept Kicad: clone this project, go through gerber and send that to your supplier.
  To get an idea of how to accomplish it might help to watch https://www.youtube.com/watch?v=ENmDnoKs2hM
* or visit https://aisler.net/p/IRBRWUAC. Note that the author has no relation to Aisler.
  It was chosen because their production was considered close at time and place of writing.

**Tips:**

* Start soldering with J1
* When using Ice Tower Cooler cables are a bit short. To get around: Unmount fan, rotate 90° clockwise and mount again. Be careful not to over-tighten screws!
* For Ice Tower Cooler noise can be reduced siginificantly by using 3.3V supply on J1 (as written in the handbook). With reduced voltage I never saw CPU temerature rising above 45°
* If space is limited one might want to use a 90° variant of J2: ![90-degree](https://user-images.githubusercontent.com/2571823/75151342-c1bc8800-5706-11ea-9086-58c96e7bd83e.JPG)

