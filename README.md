# Sonic STe

Sonic 1 for the Atari STe and Mega STe. Still an alpha :)
Requires 4 MB of RAM: sorry about that, but it's a luxury we can afford in 2026 :)
A 2 MB version is currently being tested.

Only Green Hill Zone Act 1 is included for now.

Tested with TOS 1.62 on STe and TOS 2.05 on Mega STe.

[Download alpha 0.8](./Sonic-STe-0.8-alpha.zip)

Unzip and run 'SONIC.TOS' from the 'SONIC08' folder. Please keep the data files and subfolders alongside it.

## Controls

Left/right arrows to move, space to jump or joystick and fire work too.

- P: cycle parallax off / light (mountains) / full background
- M: switch between 8 and 16 MHz on Mega STe
- R: restart
- Esc: quit

The game starts at 8 MHz with parallax off. P and M briefly show the current setting in the HUD. A regular STe stays at 8 MHz of course.

## Speed

Rough FPS in GHZ1, based on Hatari tests with sound on. It varies with the scene:

- 8 MHz: around 27-34 fps with parallax off, 17-21 with light, 9-10 with full.
- Mega STe at 16 MHz: around 37-44 fps with parallax off, 27-29 with light, 14-16 with full.

## Credits

Original game by SEGA / Sonic Team. This is a free, unofficial fan project.

Based on Sonic Retro's [s1disasm](https://github.com/sonicretro/s1disasm). Thanks to its contributors. Uses flamewing's [mdcomp](https://github.com/flamewing/mdcomp) to decompress the Mega Drive data.

Tools: [Hatari](https://www.hatari-emu.org), [EmuTOS](https://emutos.sourceforge.io), GCC m68k-atari-mint ([FreeMiNT](https://freemint.github.io)), [Unicorn Engine](https://www.unicorn-engine.org).

Some useful references:

- Douglas Little: [AGT](https://bitbucket.org/d_m_l/agtools)
- Jeffrey Young: [Hardware Phase Scrolling](https://github.com/jayoung99/Atari-STE-Hardware-Phase-Scrolling)
- Leonard / Arnaud Carré: [Graphics Tricks from Boomers](https://arnaud-carre.github.io/2024-09-08-4ktribute/)
- The Paranoid / Paradox: [The Atari ST(E) BLiTTER in brief](https://www.atari-wiki.com/index.php?title=The_Atari_ST(E)_BLiTTER_in_brief_by_The_Paranoid_of_Paradox_2012)
- Zeme: [Sync scrolling](https://blog.subspace.nl/2026/03/18/sync-scrolling.html)
- Condense: [Sonic GX](https://www.pouet.net/prod.php?which=105245) for Amstrad Plus / GX4000
