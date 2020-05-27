---
title: Hack into to most WI-FI without victim interaction
layout: page

---
## Get access to most WI-FI without victim interaction

------------------

### The scenario

-------------------------

*Karen*  was playing watchdog and there he saw a man who can get onto any system. He thought.... What if he hacked into any network in neighbour ? 

----------------------

### The Solution

-----------------------

Well I can't fully fulfill his wish. But yes I can partially do that . Using a script by v1s1t0rsh3r3 called "Airgeddon"  and the attack is known as `Pixie-Dust`. But first install kali using this tutorial <br>  So let's start karen... Umm he is asleep... <br>

Steps - <br>

- Clone the repo `sudo git clone https://github.com/v1s1t0r1sh3r3/airgeddon.git`
- Then change the directory to that `cd airgeddon` 
- Run the script `bash ./airgeddon.sh`
- It'll automatically check for necessary dependencies. Kali has most of them. But if not you can install them by `sudo apt <package name>` 
- After updates are complete. On the next screen choose a Wireless adapter which supports **Packet Injection** . Here is a [list](https://null-byte.wonderhowto.com/how-to/buy-best-wireless-network-adapter-for-wi-fi-hacking-2019-0178550/) . This capability is a **must** for pixie-dust attack.
- Put your adapter in monitor mode
- On the next screen *Explore* for wifi networks. When you see your desired network on screen tap `ctrl+c` . 
- Then choose your network from the generated list
- Choose **Bully Pixie-WPS** . 
- Keep the defaults or set your desired path and timeout
- And **Voila** The rest of the attack will be initiated automatically 

-------------------------

### Notes

-----------------------

- The adapter **MUST** support packet injection
- The Victim router **MUST** have WPS enabled and a vulnerable hardware

---------------

### Resources 

------------------------------

- The repo for Airgeddon > [GitHub](https://github.com/v1s1t0r1sh3r3/airgeddon)
- A detailed post on [Pixie dust attack](https://forums.kali.org/showthread.php?24286-WPS-Pixie-Dust-Attack-(Offline-WPS-Attack)) 

---------------------

### Lesson

------------------------------

> <u>Hacking is born to break rules</u>