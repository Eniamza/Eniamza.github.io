---
title: Make a lifeline for linux to bring it back from dead
layout: page

---
## Make a lifeline for linux to bring it back from dead

------------

### The Scenario

---------------------

*Karen* holds a record for breaking his computer. Even if he tries to install "Firefox" he breaks the whole OS. Each time he completely resets the OS using his [Android Phone](https://open.lbry.com/@Enilog:f/Turn-your-android-into-a-bootable-media:f?r=6KdNK7UG4PAyMrQYNfporKEMXhbZmQkx) . But  <br>

> <u>there is always a workaround</u>  <br>

--------------------

### The Solution 

-----------------------------

Timeshift comes to rescue . It is a snapshot feature for linux distros.. It can really take your OS back from the dead. <br>

So let's start <br>

- Add the repo using this command - `sudo apt-add-repository -y ppa:teejee2008/ppa` 
- Update using - `sudo apt-get update` 
- Install with - `sudo apt-get install timeshift` <br>

**For Other Distros** : [32 bit](https://dl.dropbox.com/u/67740416/linux/timeshift-latest-i386.run?dl=1) or [64 bit](https://dl.dropbox.com/u/67740416/linux/timeshift-latest-amd64.run?dl=1) 

--------------------------

### The Backup

-----------------------

The backup and restore process is quite easy .. Even Karen is good at it..

- Launch Timeshift with root permission
- There will be two options for backup. For our - `Back from the dead` concept we will use `RSYNC` which is able to take a exact clone of system.. *Takes strage and time*
- Choose Backup location , *Where you have plenty of space*
- Choose schedule of backup.. I recommend **One daily** 
- Choose exclusions for backups
- And **Voila** setup finished
- For `Manual Backup` Click `Create` in upper left

----------------------------

###  The Restore

---------------------

There are two kinds of restore.. <br>

<u>**1. While OS is not dead**</u> <br>

- Click on a already created snapshot from home
- Click Restore
- Confirm changes
- **Voila**  <br>

<u>**2.While OS is Dead**</u> <br>

- Make a live bootable USB with rufus 
- Boot into Linux from USB
- Install Timeshift
- Browse for backed up snapshot
- Select and click restore

---------------------------------------------

### Limitation

------------------------------

If you already fried up or bricked your PC . It can not fix that. You need to **Boot** .

---------------------------------

### Resources 

---------------------------------

- Read More about [Timeshift](https://community.linuxmint.com/software/view/timeshift)
- Read [Hack using Android](https://open.lbry.com/@Enilog:f/Turn-your-Android-into-a-hacking-device-without-Root:8?r=6KdNK7UG4PAyMrQYNfporKEMXhbZmQkx) 

----------------------

### Lesson

---------------------------

> <u>Think before Doing.</u>



