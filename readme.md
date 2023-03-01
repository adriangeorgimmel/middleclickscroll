# Middle Click Scroll Script for Linux

This script allows you to scroll using your middle mouse button on Linux systems that use X11.

## Usage

The changes to xinput are not persistent so the script needs to be run on every boot, i a cronjob for this.
Once the script executed, you can use your middle mouse button to scroll in any application that supports scrolling.

## Configuation

In the script you need to set your xinput device id, it can be found via this command: xinput --list

## Disclaimer

This script is provided as-is, without any warranty or support. Use at your own risk.
