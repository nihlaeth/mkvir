mkvir
=====

Automating the creation of virtual machines with libvirt

Getting started
=========

Copy the mkvir script to a directory in your path (/usr/bin for example).

Make sure you know where your images are. /root/images is the default location, 
so it'd be easiest to place them there.

Create a logical volume group (default name is vgvirt).

You have to be root to execute the commands needed.

Type mkvir -h for help.

Type mkvir -i for interactive mode.

To Do
==========
* add more images
* add some detection for images (do they exist?)
* move images list to a configuration file
* make errors recoverable by enabling the user to pick which commands are executed
* enable the user to pick the number of lvdisks

Supported operating systems
==========
Right now the only options are Slackware, Debian, and Knoppix. It's pretty easy to add your own image though.

Support
==========
If you have questions, contact nihlaeth at github.
