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

Run the following command in your Binary Ninja plugins directory:
```bash
git clone https://github.com/ZetaTwo/binja-gameboy.git
```

## Minimum version

This plugin has only been tested on the following version of Binary Ninja:

* release - 2.2.2487

## References

* [Gameboy Project]()
* [Gameboy Pan Docs](http://bgb.bircd.org/pandocs.htm)
* [Gameboy opcodes](https://www.pastraiser.com/cpu/gameboy/gameboy_opcodes.html)  


## License

This plugin is released under a [MIT](LICENSE) license.
