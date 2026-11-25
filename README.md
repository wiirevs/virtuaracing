# Virtua Racing for Wii

Virtua Racing (Sega, 1992, Arcade), ported to the Nintendo Wii by [WiiRevs](https://wiirevs.com).

This is a native port, not an emulator: the game's own program runs as native Wii code.

## Download

Get `virtuaracing.zip` from [Releases](../../releases/latest).

## Bring your own ROMs

WiiRevs doesn't include or link to any game ROMs. You need the game's ROM files, as the MAME `vr` set, plus the Model 1 I/O board's `epr-14869.25` (MAME's `model1io`), dumped from a board you own.

## Install

1. You need a Wii with the [Homebrew Channel](https://wiibrew.org/wiki/Homebrew_Channel) and a FAT32 SD card. [Wii Hacks Guide](https://wii.hacks.guide) explains how.
2. Unzip `virtuaracing.zip` to the root of the SD card. That gives you `apps/virtuaracing/`.
3. Copy your `vr` ROM files into `sd:/wiirevs/virtuaracing/`, and `epr-14869.25` into `sd:/wiirevs/model1io/`.
4. Start Virtua Racing from the Homebrew Channel.

The game checks its files when it starts and says which are missing.

## Controls

Hold the Wii Remote sideways, D-pad on the left. Tilt it (or press the D-pad up and down) to steer, 1 accelerates, 2 brakes, the D-pad's right and left shift up and down, A changes the view, + starts, - inserts a coin. A GameCube controller or a Classic Controller steers with the stick: A and B accelerate and brake, R and L shift, X changes the view. HOME (Z on the GameCube controller) opens the menu: controls, picture, volume, free play and the arcade's own Test Mode.

## Feedback

Found a problem or have a question? Use [Issues](../../issues) or [Discussions](../../discussions).

## More

All the games: [wiirevs.com](https://wiirevs.com)

Virtua Racing is a trademark of Sega. Nintendo and Wii are trademarks of Nintendo. WiiRevs isn't affiliated with or endorsed by either.

Third-party licences are in `apps/virtuaracing/licenses/`.
