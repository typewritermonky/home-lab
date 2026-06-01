# Metasploitable 2 Setup #

## Steps - Installation
1. Download and extract the Metasploitable file from (https://sourceforge.net/projects/metasploitable/)
2. Open VirtualBox -> New -> Virtual machine name and operating system
   - Name: Metasploitable 2
   - Type: Linux
   - Version: Ubuntu (64-bit) 
3. Click Specify virtual hardware -> set number of CPUs to 1, RAM to 512 MB
4. Click Specify virtual hard disk -> Use an Existing Virtual Hard Disk File -> Select a Virtual Hard Disk File...
   - Find your Metasploitable .vmdk file -> Choose 
6. Finish

## Steps - Networking
1. Open VirtualBox -> Kali Linux -> Settings -> Network -> Change NAT to Host-only Adapter-> OK


## Notes
- Keep Metasploitable's resources minimal: it barely needs anything to keep it's ports open and services vulnerable.

