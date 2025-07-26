# Aluminum Pan

This project has for goal to create a simple OS to run on a Raspberry Pi 2B. I am creating this to better understand how hardware and sotfware communicate together with hopes of one day working in embeded development.

## Instalation

You can clone the repository using:
```bash
git clone https://github.com/m4x1m03/AluminumPan.git
```

### Prerequisites

To test on a Raspberry Pi, you will of course need a Raspberry Pi, and a FAT formatted SD card. 

\
To run on an emulator, you can use qemu. To install, run the folllowing command in your terminal:

```bash
apt-get install qemu-system
```

We can then use the following command to emulate the kernel image:

```bash
aqemu-system-aarch64 -M raspi2b -kernel kernel7.img -serial stdio
```


## Documentation

Specify [where](https://es.wikipedia.org/wiki/Wikipedia:Portada) people can find more documentation about your project.

All the technical information will be coming from official board docummentation:

* [BCM2836 Architecture](https://datasheets.raspberrypi.com/bcm2836/bcm2836-peripherals.pdf)
* [Cortex-A7 MPCore Processor](https://developer.arm.com/documentation/ddi0464/f/?lang=en)

## Acknowledgments

_This project has been greatly inspired by:_

* [Bztsrc](https://github.com/bztsrc/raspi3-tutorial)
* [PeterLemon](https://github.com/PeterLemon/RaspberryPi)
* [Devloped From Scartch](https://www.youtube.com/@DevelopedFromScratch)