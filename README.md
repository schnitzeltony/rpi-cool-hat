# rpi-cool-hat

Raspberry Pi 4 introduced conflicting demands when producing music:

* Cooling gets mandatory to avoid throttling
* For high quality audio a soundcard HAT is required

Since most (all?) cooling solutions do not allow stacked HATs this KiCad project suggests an adapter PCB as:

![3d-preview](https://user-images.githubusercontent.com/2571823/71328625-89d47100-251a-11ea-8788-3c4cf56e014f.png)

RPi is connected right / HAT connected left (upside-down) / cooler's fan connected to pins in the back

Note that project:

* was created by Kicad 5.1.5 as shipped by Fedora 30
* is in early stage: Nothing soldered / no tests performed yet

The only relation to Aisler author has is: their production was considered close at time and place of writing. So
* if you don't share position on earth or whatever: drop [rpi-cool-hat.kicad_pcb](rpi-cool-hat.kicad_pcb)
   to a supplier of your choice
* if your supplier does not accept Kicad: clone this project and go through gerber and send that to your supplier
* or visit https://aisler.net/p/IRBRWUAC

And author is not a proffesional layouter but awaiting PRs/issues - teach me :)
