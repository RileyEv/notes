# TB2 OS Mac Install Instructions

These instructions are to install a vagrant free version of the OS. If you do not feel confident with using brew I would recommend using the lab machines or the [vagrant setup](https://github.com/danpage/COMS20001/tree/COMS20001_2019/vagrant).

## Pre-requisites
I will assume you have already installed:

- Homebrew: https://brew.sh
- Command Line Tools for MacOS: Run `xcode-select --install`

## Instructions

1. Install Qemu `brew install qemu`
2. Add brew tap `brew tap RileyEv/homebrew-coms20001`
3. Install ARM GNU toolchain `brew install RileyEv/homebrew-coms20001/arm-none-eabi-gcc`

## ⚠️⚠️ Warning
You will need a modified makefile. This can be found at [here](https://rly.rocks/s/os-mac-makefile)

⚠️ **KEEP A BACKUP OF THE OLD MAKEFILE**. You will need this to run on lab machines and for submission.

This makefile will only work if you have followed the instructions above and you have homebrew installed in the default location. You will also have to use this makefile later on but make modifications as shown in each lab/coursework worksheet.

Changes have been made on lines 15,23,24,29,31,35,52,55
