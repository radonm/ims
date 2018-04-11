# This script will install ceph on 1 node(physical or VM).

Script is tested on CentOS 7.
* Do not use if there are old (half)working ceph installation, reinstall OS first. 
* Server must have 2 H(V)DDs - one for the operating system and one for ceph storage. 
* Before running the script make sure second block device is cleared - no existing partitions or LVM sigantures. If script complains hdd is not empty use wipefs to clear it and run it again.