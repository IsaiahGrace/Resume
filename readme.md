# Isaiah Grace

isaiah@graces.com

https://isaiahgrace.github.io/


[PDF Resume](IsaiahGraceResume.pdf)


## Technical Skills
* C
* C++
* Rust
* Zig
* Linux
* Assembly
* Bash
* FPGA
* Git
* PCB layout
* LaTeX
* Matlab
* Python
* Regular expressions
* Scheme
* SystemVerilog


## Education

Purdue University, West Lafayette IN: GPA 3.40

2019 Bachelor of Science in Computer Engineering, Minor in History


## Relevant Coursework
* Data Structures \& Algorithms
* Computer Architecture
* Microcontrollers
* Object-oriented Programming
* Functional Programming
* Artificial Intelligence
* ASIC Design
* Leadership Development


## Work Experience

### Embedded Software Developer: ASML via Actalent Services: Jul 2022 to Jun 2023
* Responsible for the design and implementation of high reliability and high performance C driver firmware, enabling next-gen semiconductor manufacturing.
* Designed, developed, and tested modular driver and subsystem components in a highly distributed and strict real-time environment.
* Assisted in verification and validation of software update packages using advanced system simulators.

### Embedded Systems Engineer: Sestra Systems: May 2021 to Jun 2022
* Responsible for the design and implementation of IoT embedded systems in a small and collaborative startup environment.
* Managed the entire software life-cycle of several key embedded software systems as lead engineer.
* Worked directly with internal stakeholders, and external clients, to scope out and specify new system capabilities.
* Designed and implemented new subsystems in a multi-threaded and multi-process distributed system.
* Reverse-engineered a BLE Bluetooth protocol to develop a custom driver and control system for off the shelf hardware.
* Integrated open source device drivers utilizing C and modern C++.
* Designed SPI, CAN, and USB hardware drivers on extremely resource constrained bare-metal microcontroller boards.

### Student Researcher: Purdue SoCET team, physical design group: Apr to Aug 2019
* Developed layout, place and route, and floorplanning workflows for the physical design of an experimental research microcontroller eventually fabricated at MIT Lincoln Labs.
* Created Custom standard cells for use in an experimental hardware obfuscation prototype.

### Grader: ECE369 Discrete Mathematics: Jan to May 2019
* Graded Discrete Mathematics course assignments covering theory of computation, formal logic, graph theory, mathematical induction, state machines, and regular expressions.

### Raft Guide: Outdoor Adventure Rafting, Ocoee River, TN: May to Aug 2018
* Guided on class IV-V whitewater. Responsible for customer satisfaction and safety in demanding and dynamic workplace environment. Certified wilderness first responder.

### Operator: Purdue Rare Isotope Measurement Laboratory: Jan 2016 to May 2018
* Collected and verified data from Purdue's linear particle accelerator. Operated the accelerator during overnight shifts, participated in maintenance, and responded to emergency shutdowns.


## Research and Project Experience

### Senior design team: Polymorphic logic: Aug to Dec 2019
* Investigated the design and integration of experimental ambipolar transistors using CMOS as a proxy.
* Personally specified, documented, and implemented the digital control modules for custom logic cells.
* Integrated the team project into the larger SoCET system on a chip for fabrication at MIT Lincoln Labs.

### MIPS dual-core processor: Sep to Dec 2019
* Designed, implemented, tested, and synthesized a MIPS-based processor featuring a five stage pipeline, and two cores with independent coherent L1 caches.
* Used SystemVerilog to implement RTL logic and testbench scripts for design validation.
* Synthesized design to target an Altera Cyclone FPGA.

### Tetris hand-held console: Mar to May 2019
* Developed an STM32-based handheld Tetris console as a member of a four-person team. Personally created an SPI driver for the embedded display using C++ and assembly.

### ASIC module for USB to AHB bridge: Nov 2018
* Collaborated to design and test a USB to AHB bridge suitable for use on an SoC.
* Personally designed and wrote SystemVerilog code for the USB receiving/decoding submodule.

### First place in ECE368: Data Structures & Algorithms "big data challenge": Oct 2017
* Designed and optimized a Huffman encoding algorithm of an arbitrarily-large input using a multi-threaded approach.
* Applied principals of data structures and algorithms to heavily optimize C code. Placed first of 83 students for fastest compression of 64GB of data.


## Leadership

### Whitewater Kayaking and Caving Consultant: Purdue Outing Club: May 2016 to Dec 2019
* Taught caving and whitewater kayaking skills from beginner through advanced levels. Organized and led expeditions.
* Ensured safe environment for all participants and practiced inclusive leadership within groups.

### Facilitator, participant: EMV sophomore leadership retreat: Sep 2016, 2017, 2018
* Participated in, and twice facilitated, a leadership retreat exploring inclusive leadership in the classroom and community.

### Eagle Scout, BSA: 2014


## Compiling this document
On Arch Linux with the `texlive-most` package group installed, this command should rebuild the document:
```shell
pdflatex -interaction=nonstopmode IsaiahGraceResume.tex
```
To automatically rebuild the PDF when the `.tex` file changes:
```shell
while inotifywait -e close_write IsaiahGraceResume.tex; do pdflatex -interaction=nonstopmode IsaiahGraceResume.tex; done
```
