![Banner image for Hardware, Microcontrollers and Sensors at University of Staffordshire](/BB_Banner_HMS_ULTRA@300x.png)
# Hardware, Microcontrollers and Sensors - STM32F407 Minimal Template for Assessment and Tutorials
A minimal project for HAL projects on the STM32F407 Discovery Board. No configuration is provided other than the automatically generated initialisation by the Cube IDE and some minor tweaks to the peripherals. The template has the oscillators configured, with the timing being sourced from the high speed external oscillator (HSE). This will require proper use of prescalers when using the timers on the microcontroller.

## First Run Instructions
Before the firmware can be executed on the target device, it will need to be built. If trying to run before building the IDE will
likely warn you that there are no recent configurations to choose from. To build, use the keyboard shortcut `ctrl` + `b` or use the hammer
icon 🔨 in the tools at the top of the UI.

Once built, click the down arrow ⬇️ next to the run arrow ▶️ and select `Run Configurations` then double click `STM32 C/C++ Application` after this the run button will become active.

## Using the Test Project
Download/Fork the project.

Explore the `main.c` file, found in `Core` -> `Src`, to perform the required activities during a tutorial which allows the use of HAL.

This project omits many additional comments which are triggered by the code generation of STM32CubeIDE, providing a minimal template to be populated by the developer.

> [!NOTE]
> In a real world use case, many files from this example would have been omitted using a .gitignore file. To locate the main source file, navigate to `Core`->`Src`->`main.c`



