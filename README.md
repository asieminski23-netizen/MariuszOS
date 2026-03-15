# MariuszOS


MariuszOS Version 1.0

The Educational Micro-Kernel For x86 Developed by Mariusz | 2026

MariuszOS is an operating system that is free to use and is made for learning. It helps developers see how a basic system works with the x86 hardware manages memory and handles user input by removing the complexity of systems.

### System Design

MariuszOS is built to be simple so that students and hobbyists can easily read and understand the code.

*   **Bootloader**: A made sequence that helps the CPU switch from real mode to protected mode.

*   **Kernel**: The core part that starts the hardware and handles low-level interrupts.

*   **Memory Manager**: It checks the system BIOS during boot to find out how much RAM is available.

*   **Command Interpreter**: A built-in shell that lets users talk to the kernel.

### Using MariuszOS

When you start MariuszOS it shows a greeting like a "Power-On Self-Test" (POST):

*   **Memory**: 217 MB found

*   **Status**: Kernel started

*   **Welcome, User. System is Live. > Root@mariuszos:~#**

### Built-in Commands

| Command    | Arguments Description                                  |

| ---------- | --------- | -------------------------------------------- |

| help       | None      | Shows the manual for all commands. |

| Echo       | \[text]   | Prints text, to the output.           |

| Ram        | None      | Tells the kernel how physical memory it found. |

Calc       | \[n1] \[op] \[n2] | Does 16-bit integer math (+, - \* /).     |

| Clear      | None      | Clears the VGA buffer to reset the screen.   |

Reboot     | None      | Restarts the CPU.                             |

| Shutdown   | None      | Sends a signal to turn off the hardware.

### Running the OS

MariuszOS works best with x86 emulation. For the experience use Bochs but anything else should also work.

*   **Get the Image**: Download mariuszos.iso or floppy.img.

*   **Set Up Emulator**: Choose "/Unknown" as the guest OS and use at least 64MB of RAM.

*   **Start**: Attach the image as the boot drive and start it.

copyrighted by me, pls dont steal amigo?
