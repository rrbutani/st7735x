# st7735x
[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Frrbutani%2Fst7735x%2Fbadge&style=for-the-badge)](https://actions-badge.atrox.dev/rrbutani/st7735x/goto)

Modified ST7735R driver that supports the [1.44" 128x128 variant of the screen](https://www.adafruit.com/product/2088).

Call `ST7735_InitR(INITR_144_GREENTAB)` to use with the 1.44" variant of the screen.

### Running the examples
This project uses [tm4c-llvm-toolchain](//github.com/rrbutani/tm4c-llvm-toolchain) (tlt).

Modify the [`#define` for `SCREEN_INIT`](src/main.c#L833) to match your screen.
