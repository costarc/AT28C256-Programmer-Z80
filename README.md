# AT28C256-Programmer-Z80
This project contains code to program AT28C258 EEPROM.

## 📖 The Book

This project is **Chapter 5, "AT28C256 Programmer"**, in a book:

**Chips, Code, and Cartridges: Turn Curiosity into Creation with 13 Hands-On Projects, from 8-bit Classics to FPGAs**

It walks through thirteen of my own hardware and software projects, from 8-bit classics to FPGAs, for beginners and curious makers. Each chapter explains how one project works and how to build it, with colour diagrams and real code from its repository.

### 👉 [Get the book on Amazon](https://link.amazon/B013Yaq9y)

<sub>As an Amazon Associate, the author earns from qualifying purchases. Buying through this link
supports these projects at no extra cost to you.</sub>

The code implements routines to disable Software Data Protection (SDP), write file to the EEPROM, then enable SDP to avoid the data being written by mistake.

This code implements a command line program for MSX Computers, however the logig to operate the EEPROM is built in and could easily be ported to other paltforms or devices.
