# norns-shield

![](images/norns-shield-black.jpg)

minimal/tiny open-source/DIY shield for Raspberry Pi boards, providing hardware compatibility with the [norns](monome.org/norns) ecosystem.

- audio codec: CS4720
- audio jacks: 3.5mm stereo in/out, line level
- OLED: NHD-2.7-12864WDW3
- 3x pushbuttons, 3x rotary encoders

see the full [BOM on Octopart](https://octopart.com/bom-tool/Q3rQej3x)

see [https://llllllll.co/t/diy-norns-shield](https://llllllll.co/t/diy-norns-shield/27638) for discussion.

[monome.org](https://monome.org)

SMD-populated PCB available from [monome.org](https://market.monome.org)

**200131 update:** tip/ring on audio IO are now swapped around. This will make
left/right work as per the default, out of the box Norns image.

If you are using an older shield than 200131, and want to reverse the audio routing
such that panning works correctly, place an empty file called `reverse.txt` in the
home directory on your norns. (Eg: SSH into norns, and type `touch
reverse.txt`). Restart the norns engines from the UI, and you should have
correct routing.

![](images/norns-shield.png)

![](images/norns-shield-side.jpg)

## assembly

for SMD-populated circuit.

parts shown (header already soldered to OLED)

![](images/assembly/ns-0.jpg)

first solder the OLED header. then the encoders, and keys.

![](images/assembly/ns-1.jpg)

![](images/assembly/ns-2.jpg)

then attach the pi header to the other side and solder as shown.

![](images/assembly/ns-3.jpg)

attach the screen to the top.

check the forum thread above for the newest disk image.

