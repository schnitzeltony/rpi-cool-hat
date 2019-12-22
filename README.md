# rpi-cool-hat

Raspberry Pi 4 introduced conflicting demands when producing music:

* Cooling gets mandatory to avoid throttling
* For high quality audio a soundcard HAT is required

Since most (all?) cooling solutions do not allow stacked HATs this KiCad project suggests an adapter PCB as:

![3d-preview](https://user-images.githubusercontent.com/2571823/71314772-52e55900-244f-11ea-86db-42d5223a4f84.png)

RPi is connected right / HAT connected left (upside-down) / cooler's fan connected to pins in the back

Note that project:

* is in early stage: No PCBs ordered yet / nothing soldered / no tests
* was created by Kicad 5.1.5 as shipped by Fedora 30
