# Ubuntu-Virtual-Box-Install
Installing and running Ubuntu 16.04.2 in Virtual Box 5.1.22


Installing Virtual Box
1. Visit https://www.virtualbox.org/wiki/Downloads
2. Click on "Windows Hosts" under the Virtual Box Binaries section
3. Run or save the executable file
4. Follow the install wizard, choosing the install options as you wish (Components, Install Location, Start Menu/Desktop icons, etc...). Installation may take several minutes, and User Account Control will likely ask permission to make changes.
5. After installation, you can choose wheter or not to run Virtual Box.

Downloading Ubuntu
1. Visit https://www.ubuntu.com/download/desktop
2. Click on the Download button for Ubuntu 16.04.2 (alternatively, you can use a torrent client with the Alternative Downloads and Torrents link below the Download button)
3. You will be redirected to a page where you can choose to donate. You can still download Ubuntu for free using by either setting all fields to $0 or clicking the "Not now, take me to the download" link at the bottom of the form.
4. you'll then be brought to a new page, where a download window should automatically pop up (there is a "download now" link if this doesn't happen). Note: this is a 1.4GB file, so depending on your computer and network speed, this may take a few minutes.

Running Ubuntu from within Virtual Box
1. According to the Ubuntu site, you'll need to meet the following system specs:
    2 GHz dual core processor (or better)
    2 GB system memory (or more)
    25 GB of free hard drive space (or more)
    Internet access is recommended, but not required.
2. Run Virtual Box
3. On the top left, Click on New to create a new virtual machine
4. A window will pop up with options for Name, Type, and Version.
  Choose the desired name, then for Type select Linux, and Version will be Ubuntu (32-bit)
5. Next will be to select the amount of memory (RAM) to use with the virtual machine. 
6. After selecting the amount of RAM to use, you'll create a virtual hard disk. You can use an existing file, create a new one, or not add. For this, we'll be creating a new virtual hard disk.
7. If you're only running Ubuntu through Virtual Box, and not another, just choose the first option - VDI (VirtualBox Disk Image)
8. Now you'll choose between creating a dynamically allocated or fixed size.
  Dynamically allocated will only use the amount of storage needed (until it reaches a given fixed size)
  Fixed size will take up exactly what you set. (for this, we'll be using fixed size)
9. Now comes the step to actually set the virtual hard disk space. The default is 10GB. Select an amount that isn't too large for your current machine, and click Create.


