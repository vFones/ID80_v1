# IDOBAO ID80

![ID80v1 in action](https://i.imgur.com/8Ct49LW.gif)

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
