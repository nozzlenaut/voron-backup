# Voron 2.4 configuration backup

This repository is the automated configuration backup for my Voron 2.4 350.

It is primarily here so I have a readable history of printer configuration changes and a recovery copy if the host or storage dies. It is **not** intended to be a drop-in configuration for another printer; hardware, pins, MCU IDs, offsets, and macros are specific to my machine.

## What is this backed up with?

The repository is maintained by [Klipper-Backup](https://github.com/Staubgeborener/klipper-backup), which can automatically commit Klipper configuration changes to GitHub.

## If you're browsing for ideas

Feel free to use individual macros or configuration patterns as references, but verify everything against your own printer before copying it. In particular, do not reuse MCU serial IDs, pin mappings, motion limits, offsets, or heater settings blindly.

For the Android-host experiment that currently runs this printer, see [AndroidKlipper](https://github.com/nozzlenaut/androidklipper).
