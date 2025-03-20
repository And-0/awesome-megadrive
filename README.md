# Awesome Mega Drive Development

A curated list of useful resources for Mega Drive programming.

Despite being over 30 years old, the Sega Mega Drive (or Genesis) is still alive and kicking. A community of passionate fans has kept the 16-bit dream alive by releasing new projects and games throughout the years. If you've also always wanted to create your own Mega Drive game, then here is a list of various resources to help get you started!

Feel free to submit a pull request if you have anything to add to the list.

## Contents

* [Documentation and Articles](#documentation-and-articles)
* [Programming](#programming)
	* [Frameworks](#frameworks-and-compilers)
	* [Toolchains](#toolchains)
	* [Engines](#engines)
	* [Snippets and Demos](#snippets-and-demos)
	* [Tutorials](#tutorials)
		* [Assembly](#assembly)
		* [SGDK](#sgdk)
* [Tools](#tools)
* [Sound and Music](#sound-and-music)
* [Open Source Games](#open-source-games)
* [Reverse Engineering](#reverse-engineering)
	* [Disassemblies](#disassemblies)
* [Communities](#communities)
	* [Boards](#boards)
	* [Discords](#discords)
* [Extra Hardware](#extra-hardware)
* [Other Sites and Resources](#other-sites-and-resources)


## Documentation and Articles

* [Making a SEGA Mega Drive / Genesis game in 2019](https://www.gamedeveloper.com/design/making-a-sega-mega-drive-genesis-game-in-2019) - An article about current MD development
* [Mega Drive Development Wiki](https://wiki.megadrive.org/index.php?title=Main_Page) - A wiki about the technical aspects of the Mega Drive
* [Sega Genesis Manual](https://archive.org/details/Genesis_Technical_Overview_v1.00_1991_Sega_US) - A technical overview of the Mega Drive by Sega
* [Hardware Notes by Kabuto](https://docs.google.com/document/u/1/d/1ST9GbFfPnIjLT5loytFCm3pB0kWQ1Oe34DCBBV8saY8/) - SEGA Mega Drive hardware notes written by Kabuto of TiTAN during the development of Overdrive 2
* [Pushing Polygons on the Mega Drive](https://jix.one/pushing-polygons-on-the-mega-drive/) - Overdrive 2 demo polygon renderer write-up
* [Red Eyes demo technical details](https://docs.google.com/document/d/17pX_PS5uXSWoaS71JurC-DSKIV8ZAzlaP4o1jXbJ9CA/edit) - Details on the Red Eyes demo of Remute's music album Technoptimistic
* [MD Development Kit Hardware](https://www.retroreversing.com/sega-mega-drive-genesis-development-kit/) - A look at the MD development kit hardware
* [Hello, Sega Genesis](https://log.martinatkins.me/2020/01/20/hello-sega-genesis/) - A post about experimenting with MD dev (includes code examples)
* [Sega VR Revived](https://gamehistory.org/segavr/) - Reviving the unreleased Sega VR accessory
* [Porting Fantasy Zone to the Mega Drive](https://ameblo.jp/arcade-cabinet/entry-12659552849.html) - Porting Fantasy Zone to the Mega Drive (in Japanese)
* [M2 Interview on 3D Sonic the Hedgehog](https://web.archive.org/web/20170806200341/http://blogs.sega.com/2013/12/03/sega-3d-classics-%E2%80%93-3d-sonic-the-hedgehog-interview-with-developer-m2/) - Interview with M2 about developing the Sega 3D Classics version of Sonic
* [Sega Japan Sound Documents](https://hiddenpalace.org/News/Sega_of_Japan_Sound_Documents_and_Source_Code) - Technical documents on the YM2612 and the Mega Drive sound drivers
* [Digging for Treasure in Aladdin's Source Code](https://gamehistory.org/aladdin-source-code/) - An article exploring the source code of Aladdin
* [An authoritative reference on the YM2612](http://gendev.spritesmind.net/forum/viewtopic.php?f=24&t=386) - A whole pile of Japanese documentation on the YM2612
* [Exodus MD Tech Docs](http://techdocs.exodusemulator.com/Console/SegaMegaDrive/index.html) - Technical details important for emulation and development
* [The Sound Drivers of Sonic the Hedgehog](https://clownacy.wordpress.com/2021/04/18/the-sound-drivers-of-sonic-the-hedgehog/) - An article about the sound drivers used in the classic Sonic games
* [Sonic Megamix is not Sonic CD!](https://hcstealth.tumblr.com/post/13505293669/sonic-megamix-is-not-sonic-cd) - An article about what Sonic Megamix is (and isn't)
* [How I built my own Sega Mega Drive hardware dev kit from scratch](https://nestenius.se/2022/01/18/how-i-built-my-own-sega-mega-drive-hardware-dev-kit-from-scratch/) - An article about building a devkit, hardware and all.
* [16 Bits Homebrew Development Book (Spanish) (Amazon)](https://amzn.eu/d/8CSfbY8) -  Mega Drive Development Book using SGDK (In Spanish).

## Programming

### Frameworks and Compilers

* [SGDK](https://github.com/Stephane-D/SGDK) - Allows you to develop Mega Drive games in C
* [SecondBasic](https://www.sbasic.net) - Allows you to develop Mega Drive games in Basic
* [Java Grinder](https://www.mikekohn.net/micro/sega_genesis_java.php) - Allows you to develop Mega Drive games in Java
* [32x DevKit](https://github.com/viciious/32XDK) - Devkit, manuals and links for 32X development
* [NEXTBasic](https://alcatstudio.blogspot.com/p/nextbasic-compiler.html) - Page about the NEXTBasic compiler
* [BasiEgaXorz](http://devster.monkeeh.com/sega/basiegaxorz/) - The Sega Genesis Tiny BASIC Compiler
* [BlastForth](https://github.com/WildChild83/BlastForth) - Development kit for the Mega Drive using the Forth programming language
* [mdk](https://github.com/Mikejmoffitt/mdk) - Barebones megadrive development setup.
* [pysega](https://github.com/hansbonini/pysega) - Sega Genesis / Mega Drive development kit (SDK) written in Python
* [mddev](https://github.com/tapule/mddev) - A small Megadrive devkit with learning purposes.
* [GINCS Studio](https://gcup.ru/load/constructors/gincs_studio/2-1-0-407) - A tool to create text adventures and visual novels for the Mega Drive (Page in Russian)
* [MEGADEV](https://github.com/drojaazu/megadev) - A Sega Mega CD development framework
* [choice4genesis](https://github.com/haroldo-ok/choice4genesis) - A ChoiceScript clone that generates Sega Genesis ROMs; it can be used for visual novels or simple multimedia presentations



### Toolchains

* [Marsdev](https://github.com/andwn/marsdev) - Cross platform Mega Drive / 32X toolchain
* [mdcc](https://github.com/osen/mdcc) - Sega Mega Drive GCC Based Toolchain
* [SGDK for Linux](https://github.com/drojaazu/sgdk_nix) - A set of makefiles to get SGDK working on Linux

### Engines

* [KAdventure](https://kakoeimon.itch.io/kadventure) - An adventure game engine using SGDK and Python
* [BSPView](https://github.com/ehaliewicz/BSPView) - An in-progress 3d graphics engine
* [PortalView](https://github.com/ehaliewicz/PortalView) - A second-gen BSP/Portal renderer
* [SGDK Platformer Studio](https://github.com/bolon667/SGDK_PlatformerStudio) - Easy to use engine to make platformers for Sega Genesis

### Snippets and Demos

* [Samples in 68000 Assembly](https://github.com/BigEvilCorporation/megadrive_samples) - Small, discreet, complete samples for the SEGA Mega Drive in 68000 assembly
* [ArcadeTV Samples](https://github.com/ArcadeTV/megadrive-samples) - Code snippets in assembly for the Mega Drive
* [Hijacking the S&K Lock-on Cart](https://github.com/BigEvilCorporation/s3k_hijack) - How to hijack the Sonic & Knuckles lock-on cart
* [Writing ROMs using Rust](https://github.com/ricky26/rust-mega-drive) - A proof-of-concept project using Rust to write Mega Drive ROMs
* [Mega CD Raycast Demo](https://github.com/matteusbeus/RaycastDemo) - Fantom Bitmap 512 colour ray cast demo for the Sega Mega CD
* [Dci3Viewer](https://github.com/matteusbeus/Dci3Viewer) - FantomBitmap 512 Colour Image Viewer for Sega Mega CD
* [Mod Player for the Sega Mega CD](https://github.com/matteusbeus/ModPlayer) - An example of how the Sega Mega CD can be used to play MOD files

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
* [SteveProXNA](https://steveproxna.blogspot.com/search/label/SGDK) - SGDK Programming Setup and Sample


## Tools

* [Beehive](https://github.com/BigEvilCorporation/Beehive) - A complete content tool for the SEGA Mega Drive
* [MDTools](https://github.com/sikthehedgehog/mdtools) - A collection of several free tools designed to aid in development of Mega Drive homebrew
* [Genesis Code](https://github.com/zerasul/genesis-code) - Visual Studio Code Extension For Use Easily SGDK and some other tools like Tiled.
* [Color Mixer](https://github.com/Franticware/ColorMixerMD) - Color Mixer for SEGA Mega Drive
* [Sonic Retro Tools](https://github.com/sonicretro) - Collection of tools and disassemblies by the members of Sonic Retro
* [Palette Batch](https://allone-works.itch.io/palette-batch) - Converts images to use certain color palettes (made for use with SGDK)
* [240p Test Suite](https://github.com/ArtemioUrbina/240pTestSuite/tree/master/240psuite/Genesis/240p) - A test suite to evaluate upscalers and related equipment
* [TILED-Python-to-C](https://github.com/LIZARDRIVE/TILED-Python-to-C) - A Python tool to convert Tiled XML data to C for use with SGDK
* [Retro Graphics Toolkit](https://segaretro.org/Retro_Graphics_Toolkit) - A graphics tool to convert images for use on retro systems
* [TUME](https://segaretro.org/TUME) - An old map editor for 8bit and 16bit games
* [Aseprite Mega Drive Digitizer](http://gendev.spritesmind.net/forum/viewtopic.php?t=3112) - Display images from Aseprite on your CRT using the Mega Drive
* [MCD-Verificator](https://github.com/krikzz/MEGA-PRO/tree/master/mcd-verificator) - A test program for CD core accuracy verification

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
* [GENNY VST](https://superjoebob.wordpress.com/2023/05/30/genny-1-5-beta-genny-x/) - A VST for DAWs emulating Mega Drive instruments
* [Chipsynth MD emulation (Video)](https://www.youtube.com/watch?v=VLxTHYGLKY0) - Video about rigs created for chipsynth MD's emulation
* [Furnace](https://github.com/tildearrow/furnace) - A multi-system chiptune tracker compatible with DefleMask modules
* [Pseym](https://github.com/M374LX/pseym) - A retro-style YM2612 instrument editor

## Open-Source Games

* [Tanglewood](https://github.com/BigEvilCorporation/TANGLEWOOD) - A platformer made in assembly
* [5 Stars](https://github.com/sikthehedgehog/5stars) - A minimalistic shmup made in assembly by SikTheHedgehog
* [Miniplanets](https://github.com/sikthehedgehog/miniplanets) - A unique platformer made in assembly by SikTheHedgehog
* [Project MD](https://github.com/sikthehedgehog/projectmd) - Another game by SikTheHedgehog
* [Dragon's Castle](https://github.com/sikthehedgehog/dragon) - A platformer made in assembly...by SikTheHedgehog
* [Mega Grappler X](https://github.com/sikthehedgehog/meka) - And another game by SikTheHedgehog!
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
* [Fatal Smarties](https://v3.globalgamejam.org/2016/games/fatal-smarties) - An entry for Global Game Jam 2016
* [Pingouin Bleu](https://gendev.spritesmind.net/forum/viewtopic.php?t=1952) - A horizontal shmup written with SGDK
* [Downforce](https://gamejolt.com/games/downforce/162163) - A futuristic racer written in C
* [Ramless Pong](http://www.tmeeco.eu/BitShit/PONG!RAM.ASM) - Source code of Pong that does not use RAM, only CPU regs
* [xRick](https://pdroms.de/files/sega32x/xrick-sega-32x) - A clone of Rick Dangerous for the 32X
* [Wolf32X](https://web.archive.org/web/20210310175253/https://download1648.mediafire.com/x8gsragmh8og/5rpabuadg9f6i8d/Wolf32X-20140712.7z) - Source code for Wolf32X
* [Uwol - Quest For Money](https://shiru.untergrund.net/files/src/uwol_quest_for_money_source_code.zip) - Source code for Uwol
* [Doom](https://github.com/krikzz/doom-68k) - Proof of concept Doom port for Mega Drive
* [Crazy Driver](https://gendev.spritesmind.net/forum/viewtopic.php?f=8&t=1528) - A simplistic top-view driving game written in C
* [Casanova: Love mission](https://github.com/SegaMark7/Casanova-love-mission)

## Reverse Engineering

### Disassemblies

* [lory90 dissassemblies](https://github.com/lory90) - Dissassemblies of various Mega Drive games
* [Vladimir Kononovich Videos](https://www.youtube.com/watch?v=aNJtvdeVllA&list=PL9T2Lv4uZytQxcYFUG9bZ0IBSFiljVV70) - Videos on reverse-engineering (in Russian)
* [Vladimir Kononovich Tools](https://github.com/lab313ru) - Various tools for Mega Drive reverse-engineering
* [Shining Force Central](https://github.com/ShiningForceCentral) - A github with projects relating to the Shining Force games
* [TMSS Disassembly](http://www.tmeeco.eu/SMD/TMSSCODE.ASM) - A disassembly of the TradeMark Security System

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
 * [Super Splash Wave](https://www.youtube.com/playlist?list=PLoxs7x1Yn9F9G1Xz4pmti4b1NZLNI8SGn) - Youtube videos by strafefox covering the development of various games, including Mega Drive games
 * [Dithering on the Sega Genesis with Composite Video](https://www.youtube.com/watch?v=x0weL5XDpPs) - Examination of dithering and composite video on the Sega Genesis
 * [Sega Genesis Low Resolution Aspect Ratio](https://www.youtube.com/watch?v=TY8HAjJfSO0) - Examination of the Sega Genesis/Mega Drive output of low resolution games (256x224) to a CRT
 * [flamewing Github](https://github.com/flamewing?tab=repositories) - A github with various Mega Drive projects
 * [GenesisFan64 Github](https://github.com/GenesisFan64?tab=repositories) - A github with various Mega Drive and 32X projects
 * [Mega Cat Studios Blog](https://megacatstudios.com/blogs/retro-development/tagged/sega-games) - A blog on Mega Drive development by Mega Cat Studios
 * [2020 Games on Dreamcast and Mega Drive](http://segabits.com/forums/index.php?topic=3890.0) - A list of games made in 2020 for the Dreamcast and Mega Drive
