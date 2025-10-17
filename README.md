# Embedded Lab 1

Minimal STM32F407 project that drives four LEDs in sequence. The firmware is generated with STM32CubeMX and built with the provided Makefile.

## Hardware
- STM32F407 Discovery board (or equivalent) with LEDs connected to pins PE7, PE9, PE11, and PE13.

## Build
```bash
make
```

## Flash
Use your preferred flashing tool (e.g. `st-flash`, STM32CubeProgrammer) to program the generated `build/Lab1.bin` onto the target board.

## Run
After programming, the LEDs will toggle in a red -> yellow -> blue -> green loop with a 250 ms delay between changes.
