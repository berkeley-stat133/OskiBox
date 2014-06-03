OskiBox
=======

[OskiBox](http://www.stat.berkeley.edu/share/scf/oski.ova) is a virtual Ubuntu machine powered by the free software [VirtualBox](https://www.virtualbox.org/wiki/Downloads) from Oracle. It comes equipped with data analysis tools in python and R (RStudio, ipython, latex, gedit, etc.)

The following instructions describe the steps you need to follow in order to install it on your computer. 


##Set up instructions


To run the virtual machine, you’ll need the two components:

* A copy of the cloud machine in the form of a file named [oski.ova](http://www.stat.berkeley.edu/share/scf/oski.ova) (which is available through this link)

* The Oracle VirtualBox program, which is able to run the oski.ova; VirtualBox is free to download and use. 

Before starting the installation, make sure that you have access to a fast enough internet connection, because the `oski.ova` file is quite large. Airbears from within the campus works well, and you must expect up to a 15 minutes wait for the download to complete from the campus Airbears. It can take several hours from a slow home connection. 

###Here are the steps:

* [Download the latest version of Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads) on you computer and install it; the installation is a standard one: click on the installer and follow the instructions.


* [Download the oski.ova](http://www.stat.berkeley.edu/share/scf/oski.ova) file on your computer.
 

When both downloads are over, locate the VirtualBox application on your machine and launch it.
Select the drop-menu “File” and choose “Import Appliance”.
You’ll be prompted to choose a file: choose the file oski.ova that you downloaded.
Then press “Next” and them “Import”: Now the virtual machine is being assembled, which may take up to 15 minutes.
Once done, you’ll see your virtual machine listed as “OskiBox” in the main window of the VirtualBox program; select this machine and press “Start” (the green arrow above) .
Wait a few minutes and your virtual machine will be up and running with the same type of environment that you had in the cloud.

Good luck with your installation!

Troubleshooting

If the virtual machine fails to boot and you only see a black screen, your laptop may not have its hardware virtualization feature turned on. If so, you’ll need to change this setting in your computer’s BIOS. To do so you can try these instructions based on Red Hat instructions:

Reboot your computer. Right when the computer is coming up from the black screen, press Delete, Esc, F1, F2, or F4. Each computer manufacturer uses a different key but it should show a brief message at boot telling you which one to press. If you miss it the first time, reboot and try again. It helps to tap the key about twice a second when the computer is coming up.
In the BIOS settings, find the configuration items related to the CPU. These can be in under the headings "Processor", "Chipset" or "Northbridge".
Enable Virtualization. The setting may be called VT-x, AMD-V, SVM, or Vanderpool. Enable Intel VT-d or AMD IOMMU if the options are available.
Save your changes and reboot.


