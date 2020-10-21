# Btlejack firmware

This repository contains the firmware source code used by Btlejack to communicate and attack BLE connections with Micro:Bit devices.

Two versions of this firmware can be compiled:

 * a version for the BBC Micro:Bit
 * a version for BLE400 and Adafruit's Bluefruit LE boards

To compile these two versions:

```
$ make all
```

Firmware hex files are then available in the `dist` directory (not versioned). 

# Flashing

1. Plug the micro:bit into one of your USB ports and mount the micro:bit into some folder
2. Copy the desired firmware (hex-file) into the mounted folder and wait until the microbit stops blinking
3. execute `sync` and unmount the micro:bit
4. After the device stops blinking the firmware should be running

# Troubleshooting

When we received the micro:bits we encountered an issue that they seemed to not be flashable first.
We followed [those instructions](https://microbit.org/get-started/user-guide/firmware/) to fix that problem.


## Links

[micro:bit runtime docs](http://lancaster-university.github.io/microbit-docs/) | [microbit-dal](https://github.com/lancaster-university/microbit-dal) |  [uBit](https://github.com/lancaster-university/microbit)

## Build Environments

| Build Environment | Documentation |
| ------------- |-------------|
| ARM mbed online | http://lancaster-university.github.io/microbit-docs/online-toolchains/#mbed |
| yotta  | http://lancaster-university.github.io/microbit-docs/offline-toolchains/#yotta |

## BBC Community Guidelines

[BBC Community Guidelines](https://www.microbit.co.uk/help#sect_cg)
