🍓 Raspberry Pi Yocto Base
A clean starting point for building Custom Embedded Linux on Raspberry Pi using the Yocto Project.

Quick Start
To recreate this build on your machine:

Download the Yocto Source:

Bash
git clone git://git.yoctoproject.org/poky -b kirkstone
cd poky
git clone git://git.yoctoproject.org/meta-raspberrypi -b kirkstone
Set up the Environment:

Bash
source oe-init-build-env
Use my Configs:
Copy the local.conf and bblayers.conf from this repo into your build/conf/ folder.

Build the Image:

Bash
bitbake core-image-minimal

What's in this Repo?
conf/: My custom settings for the Raspberry Pi (WiFi, UART, etc.).

Commands.txt: A cheat-sheet of every command I used.

Terminal_Outputs.md: Logs to show the build was successful.

Future Plans
Add custom C++/Python applications.

Create a custom meta-layer for specialized hardware drivers.

Set up a cross-compilation SDK.