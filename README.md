# IDOBAO ID80

[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1618514380/video_to_markdown/images/video--a8685df35ad0053d2691cb3f15b74a58-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://i.imgur.com/r1yVApm.mp4 "")

A 75% hotswap keyboard with Durock V2 Stabilizer, Glorious Panda + Zealios V2 67G.

This is repository is a fork from [QMK](https://github.com/qmk/qmk_firmware), just used to backup my QMK firmware with custom RGB colors/Keymaps/Macros.
* VIA support enabled
* NKRO ON
* 1000Hz polling rate

## Usage:
Before compiling import those file in [qmk_firmware](https://github.com/qmk/qmk_firmware)/keyboards/ID80 and use QMK MSYS under Windows.

    qmk compile -kb ID80/ansi -km via

Flash with QMK Toolbox. Press TT(1) (near F12 and Insert) + ESC to enter flash mode.

## ANSI support:

* Keyboard Maintainer: [Sergey Vlasov](https://github.com/sigprof)
* Hardware Supported: IDOBAO ID80
