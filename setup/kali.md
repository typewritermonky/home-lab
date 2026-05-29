## Kali Linux Setup ##

# Steps
1. Download and extract the VirtualBox file from kali.org/get-kali
2. Open VirtualBox -> New -> Virtual machine name and operating system
   - Name: Kali Linux
   - b. Type: Linux
   - c. Version: Debian (64-bit) 
3. Click Specify virtual hardware -> set number of CPUs to 2
4. Click Specify virtual hard disk -> Use an Existing Virtual Hard Disk File -> Select a Virtual Hard Disk File...
   - Find your Kali Linux .vdi file -> Choose 
6. Finish

# Notes/Issues
- RAM was already set to 2048 MB. If it isn't, set it to that. Otherwise, keep all other default settings in that section as-is.
- You can get by with only 1 CPU, but performance might take a hit. 
