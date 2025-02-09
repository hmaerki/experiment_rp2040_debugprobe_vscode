# Debug RP2040 using VScode and DebugProbe

Experiments debugging a rp2040 using the debugprobe

## Links

* https://github.com/raspberrypi/pico-vscode

  Identifier: raspberry-pi.raspberry-pi-pico

* https://datasheets.raspberrypi.com/pico/getting-started-with-pico.pdf

  Chapter 4. Load and debug a project


## FAQ

* Could not start GDB process, does the program exist in filesystem?

  `sudo apt-get install gdb-multiarch`

* Open On-Chip Debugger. Error: unable to find a matching CMSIS-DAP device

  https://github.com/raspberrypi/openocd/blob/sdk-2.0.0/contrib/60-openocd.rules