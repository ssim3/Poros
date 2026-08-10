
**Embedded systems** are specialized computing platforms designed to perform a specific purpose or a limited class of tasks. Unlike general-purpose computers, which are highly visible and versatile, embedded systems are often integrated into larger devices such that the user may not even realize a computer is present.

**Embedded Systems vs General Computers**

The primary difference between an embedded system and a general computer (such as a desktop PC) lies in their **versatility and architectural layers**:

- **General Computers:** These are designed to solve an infinite variety of problems by executing diverse application programs. They follow a complex hierarchy: hardware at the base, followed by firmware/drivers, a full operating system (OS), and finally, various user-loaded applications.
- **Embedded Systems:** These are simplified versions of the computer model tailored for one job, such as controlling a microwave or a video game console. They typically lack the "bloat" of general computers, often operating without disk drives, complex I/O arrays, or a standard user-facing OS.

**Simple vs Complex Embedded Systems**

Embedded systems exist on a spectrum of complexity depending on their intended function:

- **Simple Embedded Systems:** At the lowest end, these may consist of a single 4-bit processor with minimal memory (e.g., 8 bytes of RAM and 256 bytes of ROM). In these designs, the application code is essentially the firmware itself, running directly on the hardware without any intervening layers. A common example is a basic sprinkler controller.
- **Complex Embedded Systems:** High-end embedded systems can be as powerful as a desktop computer. For instance, a modern mobile phone might utilise a 400 MHz RISC processor, while other systems might use a high-performance PC board running a version of Linux to execute a specialized application. These systems often involve multiple layers of firmware, drivers, and even specialized operating systems.

**The Role of Microprocessors and Microcontrollers**

The choice between using a **[[Microprocessors]] (MPU)** or a **microcontroller (MCU)** is central to embedded design:

- **Microprocessors (MPUs):** A microprocessor is the fundamental computing core but **cannot operate on its own**. It requires external components, including RAM for variables, ROM for the program, I/O devices, and clocking circuitry. MPUs are often chosen for complex embedded systems because they offer the absolute most in flexibility and performance.
- **Microcontrollers (MCUs):** Also known as **Systems on a Chip (SOCs)**, microcontrollers are complete computers on a single integrated circuit. They integrate the processor unit, memory (RAM and Flash), and various peripherals (like timers and I/O ports) onto one chip. Because they are self-contained, low-cost, and small, they are the "heart" of most simple and modern embedded systems.

In summary, while a discrete MPU based design allows for high-performance customisation, adding all the necessary support chips essentially creates a "discrete microcontroller". Modern high-end microcontrollers have evolved to a point where they can now perform nearly any task a traditional microprocessor can.

**Microcontrollers do include processors within them.**

A microcontroller is essentially defined as a **microprocessor surrounded by on-chip peripherals**, all integrated onto a single integrated circuit (IC). Because they contain all the necessary components of a computer on one chip—including the processor core, memory (RAM and ROM), and I/O devices—they are also known as **Systems on a Chip (SOCs)**.

Key details regarding the relationship between the two include:

- **Integration:** While a standalone microprocessor typically requires external components like RAM, ROM, and clocking circuitry to function, a microcontroller integrates these elements alongside the processor unit on the same piece of silicon.
- **Processor Core:** The internal "heart" of a microcontroller is its processor core, which executes the instructions of a program. For example, the **SX52 microcontroller** contains a RISC processing unit, while other microcontrollers might use a variant of a classic processor like the **6502** or **8051** as their internal core.
- **Purpose:** The integration of the processor with other hardware makes microcontrollers ideal for **embedded systems**, as they provide a low-cost, small, and self-contained computing solution.