# MASSIO
Matrix Arranged Soc System &amp; Massive I/O

For more details please see its Wiki.

This project is a basic and experimental prototype, to study capabilities of a very simple to build multiprocessing architecture, physically as a 3D structure, using an uniform matrix arrangement of small SoC chips (System on Chip). The main goals are three:

- To perform parallel processing having a high messaging connectivity between SoCs. A distributed Message Passing micro-Kernel supports the upper layer of any application to develop (in C/C++ language).
- To have massive, parallel and simultaneous I/O access (digital and analog Input/Output pins) in a 3D physical access (imagine a 10x10x10cm cube, plenty of physical I/O pins on its six faces).
- To have flexibility to change the hardware architecture and organization of the matrix arrangement, using the SoC's logic and analog reconfigurability (using Verilog as Hardware Description Language).

This architecture don't have conventional buses between SoCs and with the external world (as read/write memory or I/O cycles), neither a central UMA (Uniform Memory Access) for SMP (Symmetric Multri Processing), therefore this is not a SMP Architecture.

One of the typical applications of this hardware is to implement ANNs (Artificial Neural Networks) software algorithms, where parallelism and massive I/O are needed.
