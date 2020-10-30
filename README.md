- Firmware and bootloader for [SoundForce THT Braids](http://sound-force.nl/?page_id=3179) with clockwise encoder rotation and updated (aug 20) encoder GPIO pinout.

- ## *Not checked, <s>my orders didnt come</s> didnt finish to assemble yet* - ordered 103CBs from Robotdyn in summer 20, looks to be working with a generic Stlink v2 clone

- if something goes wrong, let me know __update aug 20__: been told the old version (stock encoder gpio pinout) worked as of late july 20

- compiled with Virtual Box 6 on Lubuntu 20.04 - see [Mutable dev env](https://github.com/pichenettes/mutable-dev-environment)

- To be flashed with an STLink V2 or clone


# files

Every folder consists in `/braids` and `/braids_bootloader`subfolders, containing the built files in their respective dirs, with wav and hex firmwares for each.

- ### [/braids-stock-tht-build](https://github.com/pierstu/braids_tht/tree/master/braids-stock-tht-build) 

contains portage from original Braids files by Emilie Gillet (emilie.o.gillet@gmail.com) in her [Eurorack GH repo](https://github.com/pichenettes/eurorack)

- ### [/braids-bees-tht-build](https://github.com/pierstu/braids_tht/tree/master/braids-bees-tht-build) 

contains portage from Tim Churches' [Bees in the Trees](https://github.com/timchurches/Mutated-Mutables) firmware + bootloader

- ### [/braids-renaissance-tht-build](https://github.com/pierstu/braids_tht/tree/master/braids-renaissance-tht-build) 

contains portage from Tim Bourns' [Renaissance](https://burns.ca/eurorack.html) firmware + bootloader

### Best for a first flash certainly in the .hex in [`braids-stock-tht-build`](https://github.com/pierstu/braids_tht/tree/master/braids-stock-tht-build) 
