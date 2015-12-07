# Unattended-Ubuntu-Seed-Script
Unattended-Ubuntu-Seed-Script for Ubuntu 14.04.3 Server LTS amd64 - Trusty Tahr.
create-unattended-iso.sh script will create an unattended Ubuntu ISO from start to finish
seed file contains all the answer for the installer with custom LVM partitioning.
start.sh script is copied to $username directory to be run later.

based on **Rinck Sonnenberg (Netson)** work

## Usage

* From your command line, run the following commands:

```
$ wget https://raw.githubusercontent.com/almusaddar/Unattended-Ubuntu-Seed-Script/master/create-unattended-iso.sh
$ chmod +x create-unattended-iso.sh
$ sudo ./create-unattended-iso.sh
```