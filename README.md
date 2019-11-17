
kkmoon858d
==========

Custom firmware for the KKMoon 858D (ATmega).

This is the custom firmware for the 'Youyue 858D+' from https://github.com/madworm/Youyue-858D-plus adapted to the KKMoon 858D hardware.

There is a 'user manual' of sorts in the 'Docs' folder.



Please note:

Although this device looks very much like ones sold by 'Atten' and others, the innards
are not necessarily the same. The heater / wand are probably the same, but I know that
e.g. the 'Atten 858D' uses a different mainboard with a different brand micro controller.

Naturally, this firmware will only work 'as is' for the exact mcu / mainboard combination I have (EFED REV1.6 PCB000033).

Work in Progress
================
This version is ported to and working on the KKMoon 858D hardware, but I do not own a thermometer to measure the air temperatures and so can't check if the displayed temperatures are even close to correct.

The heater control parameters are unchanged from the older settings for the Youyue hardware and could use some tuning, at the moment there is some overshoot in temperature control.

Compiling/Development
=====================
There are currently three options available, choose your preferred environemt:
* Use the [Arduino IDE](https://www.arduino.cc/en/Main/Software), make sure you do ISP Upload and _don't_ use the arduino bootloader.

---

Safety information / disclaimer:
================================

Making any modifications to this device may cause you irreversible physical harm or worse.
You do this at your own risk.

There is a significant risk of lethal electrical shock, so if you still insist of doing so, make sure to
ALWAYS UNPLUG THE MAINS CABLE before dismantling the device. Check repeatedly.

If you have an isolation transformer - do use it.

