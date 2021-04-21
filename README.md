# Propeller-2 TMS9918A VDP Emulator

The [TMS9918A](https://en.wikipedia.org/wiki/Texas_Instruments_TMS9918) is the video display processor used,
among others, in the TI-99/4A and MSX computers, ColecoVision and original Sega SG-1000 consoles.

This code implements a nearly full-featured emulation for the [Parallax Propeller-2](https://www.parallax.com/propeller-2)
microcontroller with PAL/NTSC composite, s-video and VGA output in a single cog.

![](screen1.png?raw=true) ![](screen2.png?raw=true)

Examples usage is included with the tms9918_demo.spin2 file which demonstrate the graphics modes
and basic animations.

**Supports:**

 * Text Mode
 * Graphics Modes 1 and 2
 * Multicolor Mode
 * Sprite coincidence
 * 5th sprite flag and number
 * Interrupt status flag

**Limitations**

 * Registers and sprite changes takes effect at the beginning of each scanline.
 * Interrupt flag timing may not be fully compatible with the original chip.
 * Undocumented modes are not supported.

**Links:**

 * [Parallax Propeller-2](https://www.parallax.com/propeller-2)
 * [TMS9918A](https://en.wikipedia.org/wiki/Texas_Instruments_TMS9918)

