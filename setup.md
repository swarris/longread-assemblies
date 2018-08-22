---
title: Setup
---
For the workshop we use Ubuntu Linux as the main Operating System. We have created a VirtualBox image, including all the necessary tools and data. You are of course welcome to use your own Linux-based system.

## Installing the VirtualBox image

VirtualBox is a virtualization tool from VMWare and is [freely available](https://www.virtualbox.org/wiki/Downloads).

Please download the [The Ubuntu image](https://www.dropbox.com/s/pi8t7gh43itbi64/GT-workshop.vdi?dl=0) and store it on a local hard drive. A network location usually does not work, so it is better to store it locally.

## Installing the data and tools on your own Ubuntu

The list of tools used for workshop:

1. Java 8
2. Assembly-stats
3. Minimap2
4. Canu
5. Platanus
6. Mummer 4
7. Samtools & BCF tools
8. Tablet
9. Integrative Genomics Viewer (optional)

The workshop code folder contains a shell-script [installing_workshop_vm.sh]({{site.workshop_site}}code/installing_workshop_vm.sh) which installs all required packages.

The data are available from [Dropbox](https://www.dropbox.com/s/03uj6ppq0tm687v/prepared.tar.gz?dl=0). 

{% include links.md %}
