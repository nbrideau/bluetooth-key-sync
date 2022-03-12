# Bluetooth Key Sync

This tool will facilitate synchronizing bluetooth pairing keys between Linux and Windows on dual boot systems.

## Requirements

* Access to your windows partition.
* chntpw utility.
* Access to /var/lib/bluetooth/.

## TODO

* Feature: Move keys from windows to linux or linux to windows.
* Task: Convert MAC and key formats between linux and windows formats.
* Task: Identify devices which share a pairing key between mac/win with same mac addr.

## Notes


    Detect windows drive
        Detect bluetooth adapters
        Grab keys
    List shared devices.
        Move key linux to windows or windows to linux


