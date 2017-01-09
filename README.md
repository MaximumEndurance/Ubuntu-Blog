# Installing Ubuntu on Windows


![Image](https://github.com/MaximumEndurance/Ubuntu-Blog/blob/master/ubuntu-logo112.png?raw=true)



## Part 1:Creating A Live USB drive

1. Download Ubuntu version ~16. [Click Here](releases.ubuntu.com/16.04.1/ubuntu-16.04.1-desktop-amd64.iso?_ga=1.267151886.1068213053.1475231553) to download Ubuntu. 
2. Now download Universal USB Installer(UUI). This will create a live USB. Directly booting from the ISO file (that we downloaded is not possible). Link for downloading UUI
	[Download UUI](https://www.pendrivelinux.com/downloads/Universal-USB-Installer/Universal-USB-Installer-1.9.7.0.exe)
3. Run UUI. 

![Image](https://github.com/MaximumEndurance/Ubuntu-Blog/blob/master/1.PNG?raw=true)

4. Select the linux distro, here Ubuntu.
5. In the link for download location  choose the location of the ubuntu file downloaded (lies probably in your Downloads directory).
6. Select the drive letter (E, F ,G etc) of the pendrive that you inserted 
	Note: Attempt this step with caution and verify the drive letter carefully. 

![Image](https://github.com/MaximumEndurance/Ubuntu-Blog/blob/master/2.PNG?raw=true)

7. A typical conversion to live USB may take 15-30 minutes.

Part 1 complete. Congrats! 

## Part 2:Booting into Ubuntu

1. From the Start screen search for Update and Recovery --> Advanced Startup Options --> Restart Now.
2. A blue colored screen opens now.
3. Choose "Use a USB device"
4. Then select your device (preferrably knowing the brand of pen drive would work)

Part 2 complete: You are now booting into Ubuntu

## Part 3: Installing Ubuntu

1. We notice that a black screen appears with 4 options.
Choose _Try Ubuntu without installing_. 
Note: it is not in best practise to go for "install Ubuntu" directly and better to first check if our system is capable og booting into it.
2. One violet screen later you boot into the Ubuntu Desktop.
3. Tap the second icon "Install Ubuntu 16.10" (version may be different).
4. Now might be the best time to connect to the Internet. Ubuntu depends on several third-party softwares (softwares sourced out of Ubuntu) so trust it, its worthwhile to connect to the Internet.
-------------If using Internet requires logging into then
 Launch Firefox (from the left side vertical bar you see --> Go to university URL and login) )

Part 3 complete : Installation window opens up.

## Part 4: Selecting right options while installing

For most of the part you will have to go on clicking next, next and next here.

 Click continue on the first page.     

![Image](https://github.com/MaximumEndurance/Ubuntu-Blog/blob/gh-pages/Screenshot%20from%202017-01-09%2001-01-17.png?raw=true)

Here it is recommended that you check the options for _Installing updates_ as well as _Installing third party software_.
Leave the "Turn off Secure Boot" option disabled for now.

![Image](https://github.com/MaximumEndurance/Ubuntu-Blog/blob/gh-pages/Screenshot%20from%202017-01-09%2001-01-56.png?raw=true)

 Be careful with the second window though.

![Image](https://github.com/MaximumEndurance/Ubuntu-Blog/blob/gh-pages/Screenshot%20from%202017-01-09%2001-04-34.png?raw=true)
	
You will have 2 options
a) Choose to install alongside Windows Boot Manager
b) Erase disk and install Ubuntu
	
**Choose a)**
Note: If you choose b) you will end up  format your hard disk and wipe out Windows.

 Partition page appears 


Double click on the partition that has enough space for installing Ubuntu(~8GB)

![Image](https://github.com/MaximumEndurance/Ubuntu-Blog/blob/gh-pages/Screenshot%20from%202017-01-09%2022-48-54.png?raw=true)

Ignore the prompt for swap space as of now (or you can go back or select swap instead of root in _"Mount Options"_)

![Image](https://github.com/MaximumEndurance/Ubuntu-Blog/blob/gh-pages/Screenshot%20from%202017-01-09%2022-49-20.png?raw=true)

Confirm setting up of new partitions

![Image](https://github.com/MaximumEndurance/Ubuntu-Blog/blob/gh-pages/Screenshot%20from%202017-01-09%2022-49-34.png?raw=true)

Choose username and password for your laptop. (Your take here)

![Image](https://github.com/MaximumEndurance/Ubuntu-Blog/blob/gh-pages/Screenshot%20from%202017-01-10%2004-21-28.png?raw=true)
	
 For choosing time, instead of the default Kolkata, search for India time. India time is regularly updaed with the Internet time, so saves you the horrors of resetting your CPU clock again and again.

![Image](https://github.com/MaximumEndurance/Ubuntu-Blog/blob/gh-pages/Screenshot%20from%202017-01-09%2001-06-49.png?raw=true)

**Note** _This part might not appear during your installation_ .In the window for partitions, assign a size of 70-100GB for Ubuntu (it will last you for quite a while). Use the slider in the middle to adjust the partitions.
 
 Final page appears. This is the page that shows the progress of installation.

![Image](https://github.com/MaximumEndurance/Ubuntu-Blog/blob/gh-pages/Screenshot%20from%202017-01-10%2004-23-52.png?raw=true)
 
## Part 5:Restarting Ubuntu

After installation finishes, click the **Restart Now** option in the dialog box that appears.

Now we notice something different when we boot.

A violet-colored window comes up having 4 options. This window is quite similar to black-colored window we encoutered earlier.
This is called the _grub_ . 

1. The first option here loads the Ubuntu OS.
2. The second option is for Advanced Booting options (not of interest as of now)
3. The third option "Windows Boot Manager" loads into Windows.
4. The fourth option "System Setup" loads into your BIOS.

**Ubuntu** _stands for "I am what I am because of what we are"_

Welcome to the OpenSource Community!
