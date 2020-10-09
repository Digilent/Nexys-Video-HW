# Nexys Video Hardware Repository

This repository contains Vivado projects for all demos for the Nexys Video.

For more information about the Nexys Video, visit its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/nexys-video/start) on the Digilent Wiki.

Each demo contained in this repository is documented on the Digilent Wiki, links in the table below.

| Wiki Link | Description |
|-----------|-------------|
| [Nexys Video General Purpose I/O Demo](https://reference.digilentinc.com/reference/programmable-logic/nexys-video/demos/gpio) |A hardware-only project using the Nexys Video's switches, LEDs, pushbuttons, onboard OLED display and USB UART bridge |
| [Nexys Video Keyboard Demo](https://reference.digilentinc.com/reference/programmable-logic/nexys-video/demos/keyboard) |When a keyboard button is pressed/released, the value of the scan code will be converted to ASCII and transmitted to the terminal |
| [Nexys Video XADC Analog to Digital Converter Demo](https://reference.digilentinc.com/reference/programmable-logic/nexys-video/demos/xadc) |A hardware-only project using the Nexys Video's analog-to-digital converter ciruitry, and the OLED display |
| [Nexys Video OLED Demo](https://reference.digilentinc.com/reference/programmable-logic/nexys-video/demos/oled) |A hardware-only project using the Nexys Video's LEDs, pushbuttons and OLED Display written in Verilog.  |

## Repository Description

This repository contains the Vivado projects and hardware designs for all of the demos that we provide for the Nexys Video. As some demos also require software sources contained in Vitis workspaces, this repository should not be used directly. The [Nexys Video](https://github.com/Digilent/Nexys-Video) repository contains all sources for these demos across all tools, and pulls in all of this repository's sources by using it as a submodule.

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked in the table of demos, above.

Demos were moved into this repository during 2020.1 updates. History of these demos prior to these updates can be found in their old repositories, linked below:
* https://github.com/Digilent/Nexys-Video-GPIO
* https://github.com/Digilent/Nexys-Video-Keyboard
* https://github.com/Digilent/Nexys-Video-XADC
* https://github.com/Digilent/Nexys-Video-OLED
