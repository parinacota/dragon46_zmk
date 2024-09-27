ZMK configuration for dragon46 keyboard.

![](dragon46.png)
![](dragon46.jpg)

Not working / still under development
- implement a reset key? (in addition to the button on the back). Same for a bootloader key?
- mouse move not implemeneted

Update:
- soft-on / off throug dedicated GPIO button working, but with an issue: when CONFIG_ZMK_IDLE_SLEEP_TIMEOUT timeout is reached, the button cannot wakeup the keyboard and a reset (small button under the keyboard) is needed to wakeup.
