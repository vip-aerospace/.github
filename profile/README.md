# Welcome to the VIP Aerospace GitHub page! 👋

This GitHub organization is for the two VIP Aerospace teams: Laniakea, and Hokulele.

## Team Laniakea
Team Laniakea is a CubeSat development Vertically Integrated Project (VIP) at the University of Hawaii at Manoa. The purpose of the project is to produce Ke Ao, which will be the first Hawaii student-built satellite to image the Hawaiian islands. 

### General Repositories
- [keao](https://github.com/vip-aerospace/keao) The general Ke Ao repository.

### Flight Software Repositories
As Ke Ao builds upon the Artemis CubeSat kit, there is significant overlap between Artemis code and Ke Ao. As such, the flight software development team is currently refactoring and upstreaming changes to the flight software for the benefit of both Ke Ao and Artemis.
- [artemis-cosmos-rpi-fsw](https://github.com/vip-aerospace/artemis-cosmos-rpi-fsw) The COSMOS flight software that will run on Artemis' Raspberry Pi Zero. This is a fork used to upstream development to Artemis, and the upstream repository (managed by HSFL) is [here](https://github.com/hsfl/artemis-cosmos-rpi-fsw).
- [artemis-cosmos-teensy-fsw](https://github.com/vip-aerospace/artemis-cosmos-teensy-fsw) The micro-COSMOS flight software that will run on Artemis' Teensy 4.1. This is a fork used to upstream development to Artemis, and the upstream repository (managed by HSFL) is [here](https://github.com/hsfl/artemis-cosmos-teensy-fsw).
- [keao-cosmos-teensy-fsw](https://github.com/vip-aerospace/artemis-cosmos-teensy-fsw) The micro-COSMOS flight software that will run on Ke Ao's Teensy 4.1. This is a fork of the upstream Artemis micro-COSMOS flight software, and should only be developed when the Artemis flight software has been completed and upstreamed. This flight software should contain extensions to the Artemis code for Ke Ao's payloads.
- [keao-flight-software](https://github.com/vip-aerospace/keao-flight-software) An archive of the old Raspberry Pi and Teensy flight software in one repository. No longer being updated.
- [keao-teensy-fsw](https://github.com/vip-aerospace/keao-teensy-fsw) An archive of a previous attempt to upstream changes from Ke Ao to Artemis. No longer being updated.

### Ground Station Repositories
- [keao-gs](https://github.com/vip-aerospace/keao-gs) A set of GNURadio flows used to communicate with Ke Ao.

### Unit Testing Repositories
- [astrodev-serial-test](https://github.com/vip-aerospace/astrodev-serial-test) An Arduino sketch used to debug serial communications to/from an [Astrodev Lithium-3 radio](http://www.astrodevllc.com/public_html3/index.html).

### Training Repositories
- [github-workshop](https://github.com/vip-aerospace/github-workshop) A sample GitHub repository for use in Git training.
