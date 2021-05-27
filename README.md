# Awesome Mega Drive Development

A curated list of useful resources for Mega Drive programming.

Despite being over 30 years old, the Sega Mega Drive (or Genesis) is still alive and kicking. A community of passionate fans has kept the 16-bit dream alive by releasing new projects and games throughout the years. If you've also always wanted to create your own Mega Drive game, then here is a list of various resources to help get you started!

Feel free to submit a pull request if you have anything to add to the list.

## Contents

[TODO]

## Documentation and Articles

* [Making a SEGA Mega Drive / Genesis game in 2019](https://www.gamasutra.com/blogs/DoctorLudos/20191019/352537/Making_a_SEGA_Mega_Drive__Genesis_game_in_2019.php) - An article about current MD development
* [Mega Drive Development Wiki](https://wiki.megadrive.org/index.php?title=Main_Page) - A wiki about the technical aspects of the Mega Drive
* [Sega Genesis Manual](https://archive.org/details/Genesis_Technical_Overview_v1.00_1991_Sega_US) - A technical overview of the Mega Drive by Sega
* [Hardware Notes by Kabuto](https://docs.google.com/document/u/1/d/1ST9GbFfPnIjLT5loytFCm3pB0kWQ1Oe34DCBBV8saY8/) - SEGA Mega Drive hardware notes written by Kabuto of TiTAN during the development of Overdrive 2
* [Pushing Polygons on the Mega Drive](https://jix.one/pushing-polygons-on-the-mega-drive/) - Overdrive 2 demo polygon renderer write-up
* [Red Eyes demo technical details](https://docs.google.com/document/d/17pX_PS5uXSWoaS71JurC-DSKIV8ZAzlaP4o1jXbJ9CA/edit) - Details on the Red Eyes demo of Remute's music album Technoptimistic
* [MD Development Kit Hardware](https://www.retroreversing.com/sega-mega-drive-genesis-development-kit/) - A look at the MD development kit hardware
* [Hello, Sega Genesis](https://log.martinatkins.me/2020/01/20/hello-sega-genesis/) - A post about experimenting with MD dev (includes code examples)
* [Sega VR Revived](https://gamehistory.org/segavr/) - Reviving the unreleased Sega VR accessory

## Programming

### Frameworks

* [SGDK](https://github.com/Stephane-D/SGDK) - Allows you to develop Mega Drive games in C
* [SecondBasic](https://www.sbasic.net) - Allows you to develop Mega Drive games in Basic
* [32x DevKit](https://github.com/viciious/32XDK) - Devkit, manuals and links for 32X development

### Toolchains

* [Marsdev](https://github.com/andwn/marsdev) - Cross platform Mega Drive / 32X toolchain
* [mdcc](https://github.com/osen/mdcc) - Sega Mega Drive GCC Based Toolchain

### Engines

* [KAdventure](https://kakoeimon.itch.io/kadventure) - An adventure game engine using SGDK and Python
* [BSPView](https://github.com/ehaliewicz/BSPView) - An in-progress 3d graphics engine
* [PortalView](https://github.com/ehaliewicz/PortalView) - A second-gen BSP/Portal renderer

### Snippets and Demos

* [Samples in 68000 Assembly](https://github.com/BigEvilCorporation/megadrive_samples) - Small, discreet, complete samples for the SEGA Mega Drive in 68000 assembly
* [ArcadeTV Samples](https://github.com/ArcadeTV/megadrive-samples) - Code snippets in assembly for the Mega Drive
* [Hijacking the S&K Lock-on Cart](https://github.com/BigEvilCorporation/s3k_hijack) - How to hijack the Sonic & Knuckles lock-on cart
* [Writing ROMs using Rust](https://github.com/ricky26/rust-mega-drive) - A proof-of-concept project using Rust to write Mega Drive ROMs

### Tutorials

#### Assembly

* [Plutiedev](https://www.plutiedev.com) - Various tutorials on programming the 68000, Z80 and more
* [68000 Assembly Programming for the Sega Genesis](https://www.chibiakumas.com/68000/genesis.php) - Various tutorials on assembly coding for the Mega Drive
* [Big Evil Corporation](https://blog.bigevilcorporation.co.uk/2012/02/28/sega-megadrive-1-getting-started/) - A tutorial on getting started with assembly coding for the Mega Drive
* [Mode 5](https://mode5.net/Tutorials.html) - A few basic assembly tutorials
* [MarkeyJester’s Motorola 68000 Beginner’s Tutorial](http://mrjester.hapisan.com/04_MC68/Index.html) - An extensive 68000 assembly tutorial for beginners
* [Hugues Johnson Tutorials](https://huguesjohnson.com/programming/genesis/palettes/) - An assembly programming tutorial

#### SGDK

* [Ohsat Games](https://www.ohsat.com/tutorial/) - Various full project and one-off tutorials for SGDK
* [Danibus](https://danibus.wordpress.com) - Various SGDK tutorials in Spanish and English


## Tools

* [Beehive](https://github.com/BigEvilCorporation/Beehive) - A complete content tool for the SEGA Mega Drive
* [MDTools](https://github.com/sikthehedgehog/mdtools) - A collection of several free tools designed to aid in development of Mega Drive homebrew
* [Genesis Code](https://github.com/zerasul/genesis-code) - Visual Studio Code Extension For Use Easily SGDK and some other tools like Tiled.
* [Color Mixer](https://github.com/Franticware/ColorMixerMD) - Color Mixer for SEGA Mega Drive
* [Sonic Retro Tools](https://github.com/sonicretro) - Collection of tools and disassemblies by the members of Sonic Retro
* [Palette Batch](https://allone-works.itch.io/palette-batch) - Converts images to use certain color palettes (made for use with SGDK)
* [240p Test Suite](https://github.com/ArtemioUrbina/240pTestSuite/tree/master/240psuite/Genesis/240p) - A test suite to evaluate upscalers and related equipment

## Sound and Music

* [Echo](https://github.com/sikthehedgehog/Echo) - A Mega Drive Sound Engine
* [Mega PCM](https://github.com/vladikcomper/MegaPCM) - A sound driver that exclusively plays digitized audio samples through an YM2612 sound chip's DAC channel
* [Mega Drive MIDI Interface](https://github.com/rhargreaves/mega-drive-midi-interface) - Control the Yamaha YM2612 and PSG of the Sega Mega Drive via MIDI
* [MDTracker](https://github.com/corthax/mdtracker) - Native music tracker for the Mega Drive
* [MDSDRV](https://github.com/superctr/MDSDRV) - A sound driver for Sega Mega Drive
* [MML2VGM](https://github.com/kuma4649/mml2vgm) - Converts MML files to Mega Drive format
* [Lusid-Dreams](https://github.com/mic-/lusid-dreams) - A SID player for the Sega 32X
* [VGM Music Maker Primer](https://megacatstudios.com/blogs/retro-development/creating-music-and-sound-for-the-sega-genesis-mega-drive-a-primer-for-using-the-vgm-music-maker) - A primer on creating music for the Mega Drive
* [DefleMask Instrument Tutorial](https://www.youtube.com/watch?v=wS8edjurjDw) - A video guide to making FM instruments for the Sega Mega Drive

## Open-Source Games

* [Tanglewood](https://github.com/BigEvilCorporation/TANGLEWOOD) - A platformer made in assembly
* [5 Stars](https://github.com/sikthehedgehog/5stars) - A minimalistic shmup made in assembly
* [Miniplanets](https://github.com/sikthehedgehog/miniplanets) - A unique platformer made in assembly
* [Cave Story MD](https://github.com/andwn/cave-story-md) - A rewrite/port of Cave Story for the Mega Drive
* [Penguin World](https://github.com/alicesim1/Penguin-World) - A game made using SGDK
* [Lunch Break](https://github.com/GoodPraxis/lunch-break) - A game made using SGDK
* [Right 2 Repair](https://github.com/theshaneobrien/Global_Game_Jam_2020) - A 2-player game made using SGDK
* [Dr. Mario MD](https://github.com/Strugglemeat/drmariomd) - A port of Dr. Mario, made using SGDK
* [MegaDriveSnake](https://github.com/s7jones/MegaDriveSnake) - A Snake game made using SGDK
* [Moon Watcher Games](https://github.com/moon-watcher) - Various games and ports using SGDK and/or assembly
* [Tetris MD](https://github.com/NeroJin/TetrisMD) - A Tetris game made using SGDK
* [Tro-Now](https://github.com/bitbitjam/bbj2/tree/master/%5BMD%5D%20Tro-Now) - A Tron lightcycle game made using SGDK
* [Retail Clerk '89](https://www.huguesjohnson.com/rc89/) - An interactive fiction game made in assembly
* [Chris Shrigley Source Code Archive](http://shrigley.com/source_code_archive/) - Collection of code of games Chris Shrigley worked on (for educational purposes only!)
* [BattleCity Online](https://github.com/krikzz/BattleCity-online) - A port of BattleCity with online multiplayer

## Reverse Engineering

### Dissassemblies

* [lory90 dissassemblies](https://github.com/lory90) - Dissassemblies of various Mega Drive games
* [Vladimir Kononovich Videos](https://www.youtube.com/watch?v=aNJtvdeVllA&list=PL9T2Lv4uZytQxcYFUG9bZ0IBSFiljVV70) - Videos on reverse-engineering (in Russian)
* [Vladimir Kononovich Tools](https://github.com/lab313ru) - Various tools for Mega Drive reverse-engineering

## Communities

### Boards

* [Spritesmind](http://gendev.spritesmind.net/forum/)
* [Sega-16](https://www.sega-16.com/forum/)

### Discords

* [SGDK](https://discord.com/invite/hpHesQG)
* [Plutiedev](https://discord.com/invite/k79rzTz)
* [Mega Drive Developers Collective](https://discord.com/invite/QdudKChTxn)
* [SegaXtreme](https://discord.com/invite/C5TbdCH)
* [BlastEm Emulator](https://discord.com/invite/mQW4MKD)
* [DefleMask](https://discord.com/invite/bqSNKHE)
* [The Fourth Modulator](https://discord.com/invite/PSwpJ85)

## Extra hardware

* [SVP chip development](https://github.com/jdesiloniz/svpdev) - Open-source hardware boards to turn retail Virtua Racing cartridges into a "devkits", an assembler for the SVP chip DSP, sources and docs.
* [MegaWiFi](https://github.com/doragasu/mw) - WiFi enabled cartridge for the Mega Drive

## Other Sites and Resources
 * [Romhacking.net MD](https://www.romhacking.net/?page=documents&category=&platform=11) - Resources for Mega Drive development
 * [Romhacking.net MCD](https://www.romhacking.net/?page=documents&category=&platform=29) - Resources for Mega CD development
 * [Romhacking.net 32X](https://www.romhacking.net/?page=documents&category=&platform=31) - Resources for 32X development
 * [SMS Power!](https://www.smspower.org/) - Resources on Master System development