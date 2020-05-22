---
title: Fixing writing permission in NTFS formatted drive
layout: post

---
## Fixing writing permission in NTFS formatted drive

<br>

### The scenario

***

<br>
Windows (An ancient thing ) uses hard-drives formatted as NTFS.But linux and debian based systems doesn't have necessary tools for writing to NTFS formatted drives. As a result we get stucked in the middle of our sole desire of writing to those drives. This specially occurs when someone is dual booting with windows.   
So let's start the squashing. <br>

### The Solution

***

<br>
Luckily there is a fix for this stinky problem.To do that simply open a terminal by pressing -`ctrl+alt+t`. Then Run this command - ` sudo ntfsfix /dev/sda1 ` \ . Remember to replace **sda1** with your drive id. <br>

### The other solution

***

<br>
This problem generally occurs for fast boot feature in windows. To disable fast boot/startup head to this link on [HowToGeek](https://www.howtogeek.com/243901/the-pros-and-cons-of-windows-10s-fast-startup-mode/) which has a detailed post on pros and cons.
<br>
And to disable hibernation in windows Sail [Here](https://www.howtogeek.com/howto/15140/what-is-hiberfil.sys-and-how-do-i-delete-it/).
<br>

***

<br>
If you see any mistakes. Then DM me on discord - @t4shf33n#5876