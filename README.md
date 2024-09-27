ZMK configuration for dragon46 keyboard (custom PCB with a nice!nanov2, a nice!vew and a rotary encoder)
Ergo-L layout (https://ergol.org) with some adaptations on the "altgr/code" layer to fit a numpad on the right.
"Emulate" an AZERTY french keyboard, so non-standard keys are injected through key combinaisons (including alt+xxx for Windows specific chars). PC and macOS with a switch button. This is done to comply with any French computer without any configuration (including virtual machines).

![](dragon46.png)
![](dragon46.jpg)

Latest change:
- soft-on / off throug dedicated GPIO button working, but with an issue: when CONFIG_ZMK_IDLE_SLEEP_TIMEOUT timeout is reached, the button cannot wakeup the keyboard and a reset (small button under the keyboard) is needed to wakeup.

Not working / still under development
- mouse move not implemeneted (not fully supported in ZMK)
