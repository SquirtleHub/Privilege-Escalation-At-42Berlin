# How i managed to gain [SUDO] access at 42Berlin
Steps To Reproduce :
1. During boot-up press *Esc* .
2. Next you should be shown "Grub Boot-loader" (with 3 options) : 
3. [<screenshot#11>](https://github.com/SquirtleHub/-sudo-Access-At-42Berlin/blob/main/boot.jpg)
>> And here the complicated part some computers that have corrupted files during the booting or some hardware problems will makes things easier for you and you don't need to do that's much nonsense handwork because it will be automatically give you the option for the recovery mode == Root-Shell :),
and make sure that some computer have the superuser that will ask you for a username and password then you will have to force into the recovery mode how ?
4. Proceed to break into recovery mode
5. either restart the computer several times or typing nonsense until its forced into recovery mode
6. once in recovery you should be presented with the following:
[<screenshot #1>](https://github.com/SquirtleHub/-sudo-Access-At-42Berlin/blob/main/recovery.jpg)
7. and boom once you press enter you are given a root shell 
8. in root access you can add yourself to sudoers list (thanks to born2beroot project )

# Resources to prevent this + similar exploits :
* [https://cromwell-intl.com/open-source/linux-break-in-howto.html](https://cromwell-intl.com/open-source/linux-break-in-howto.html)

>> Note that 	Security is not one simple thing, it tends to be some form of an arms race !!
