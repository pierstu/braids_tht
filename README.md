- Firmware and bootloader for [SoundForce THT Braids](http://sound-force.nl/?page_id=3179)

- simple mirror for `eurorack/build` folders, you'll probably only need the binaries (.hex, .wav)

- edited and compiled for recommended 12-bit DACs, updated and recompiled with edited encoder GPIO pins in `drivers/encoder.cc` aug 2020  

- ## *Not checked, my orders didnt arrive yet* 

- ## if something goes wrong, let me know

- compiled with Virtual Box 6 on Ubuntu 20.04 

- To be flashed with an STLink V2 or clone

- Built with [Mutable dev env](https://github.com/pichenettes/mutable-dev-environment)


# files

Each folder consist in `braids` and `braids_bootloader`subfolders, containing _all_ build files: bootloaders, hex firmwares, wav firmwares.

- ### [/braids-stock-tht-build](https://github.com/pierstu/braids_tht/tree/master/braids-stock-tht-build) 

contains portage from original Braids files by Emilie Gillet (emilie.o.gillet@gmail.com) in her [Eurorack GH repo](https://github.com/pichenettes/eurorack)

- ### [/braids-bees-tht-build](https://github.com/pierstu/braids_tht/tree/master/braids-bees-tht-build) 

contains portage from Tim Churches' [Bees in the Trees](https://github.com/timchurches/Mutated-Mutables) firmware + bootloader

- ### [/braids-renaissance-tht-build](https://github.com/pierstu/braids_tht/tree/master/braids-renaissance-tht-build) 

contains portage from Tim Bourns' [Renaissance](https://burns.ca/eurorack.html) firmware + bootloader

### Best for a first flash certainly in the .hex in [`braids-stock`](https://github.com/pierstu/braids_tht/tree/master/braids-stock-tht-build) 
(original Mutable files 
