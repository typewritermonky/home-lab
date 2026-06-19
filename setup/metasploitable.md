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
   - ** Don't set this VM to NAT: you only want it to communicate to the Kali Linux VM only **

## Steps - Initial Boot
1. Open VirtualBox -> Double-Click Metasploitable 2 to power it on
2. Open the VM and login
   - Username: msfadmin
   - Password: msfadmin
3. Run ifconfig, returns the IP address of Metasploitable
   - This should return an output similar to the one shown in screenshots.md (Figure 1)

## Notes
- Keep Metasploitable's resources minimal: it barely needs anything to keep it's ports open and services vulnerable.

