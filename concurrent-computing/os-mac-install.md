# TB2 OS Mac Install Instructions

These instructions are to install a vagrant free version of the OS.

## Pre-requisites
I assume you have already installed:

- Homebrew: https://brew.sh
- Command Line Tools for MacOS: Run `xcode-select --install`

## Instructions

1. Install Qemu `brew install qemu`
2. Add brew tap `brew tap ArmMbed/homebrew-formulae`
3. Install ARM GNU toolchain `brew install arm-none-eabi-gcc`

## ⚠️⚠️ Warning
You will need to modify each makefile provided with each worksheet.

⚠️ KEEP A BACKUP OF THE OLD MAKEFILE. You will need this to run on lab machines and for submission.

1. Change line 15 to ` QEMU_PATH        = /usr/local`
2. Change line 23 to ` LINARO_PATH      = /usr/local`
3. Change line 24 to ` LINARO_PREFIX    = arm-non-eabi`
