# rem_scan_pcb

## An open source scan controller for SEMs

This PCB features two 16bit DACs to steer the electron beam of an SEM and two 16bit ADCs to acquire the image signal from up to two detectors.

It can be controlled via USB. The FTDI chip provides a virtual comport, a fast FIFO connection and a JTAG port for flashing the gateware.
Currently, only the serial port is supported in the gateware and the GUI.

Additionally, a VGA monitor can be connected for a live view of the image.
On PCBv1, only the internal blockram is used. This limits the resolution to 100x75 pixels. The image is upscaled to 800x600.

PCBv2 has external RAM and allows a native resolution of 800x600.
