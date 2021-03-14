# EarthOS-MBR
This MBR can be used to boot operating systems in SMC Computer.

## Building from source

Clone this repository using this command:

`git clone https://github.com/EarthOS-SMC/EarthOS-MBR`

Then, go to the source code directory:

`cd EarthOS-MBR`

Before the build process, you need to clone the PowerSlash compiler too:

`chmod +x sync.sh && ./sync.sh`

To build the MBR,

`./build.sh`


The binary will be saved in the `image` file. You can add it at the beginning of your virtual disk.

## Reduce output

You can reduce the output by putting `1` in the `reduce` file:
`echo 1 > reduce`
