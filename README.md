# archLinux_VM

This is a script to quickly install arch linux for virtualbox. It adds the Vbox guest additions aswell. 

## How to run and install

To run this either copy it onto the install media using another pc with ssh and scp or rebuild the arch linux iso with this script located on it. Follow the Arch Wiki guide Remastering the iso. 
I can verify that it works. 

## Added a part 2 to the repo

This adds a exact copy but makes the files system btrfs instead of ext4 for
better speed and snapshot support.

### TIPS

This works very nice with the virtualbox creatitition from terminal. Which I
will also add to the repo. 

## Caution

This is not a full proof solution it is not indented for one. It is just a
simple script for setting a Virtual Machine without having to go through the
Arch Install. For a normal desktop I still recommend using the normal install.

# DO NOT RUN ON YOUR MAIN SYSTEM
I commented the format and drive command incase someone tries to run this on there own pc. PLEASE DO NOT!!
