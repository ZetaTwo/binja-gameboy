# Gameboy Binary Ninja plugin

## Description

A Binary Ninja plugin to load Game Boy ROMs and disassemble Game Boy architecture bytecode (Sharp LR35902).

Based on [bnGB](https://github.com/icecr4ck/bnGB) by [Hugo Porcher (icecr4ck)](https://github.com/icecr4ck).

### Improvements
* Added proper IO register symbols
* Added ISR symbols
* Fixed some incorrect branching
* Fixed some incorrect addressing modes

### Todo
* Implement LLIL lifting
* Thorough testing

## Installation

Either install the plugin from the plugin manager or manually clone the repository to your plugin directory.

## Minimum version

This plugin has only been tested on the following version of Binary Ninja:

* release - 2.2.2487

## References

* [Gameboy Project](https://github.com/ZetaTwo/gameboy-project)
* [Gameboy Pan Docs](http://bgb.bircd.org/pandocs.htm)
* [Gameboy opcodes](https://www.pastraiser.com/cpu/gameboy/gameboy_opcodes.html)  

## License

This plugin is released under a [MIT](LICENSE) license.
