# EggMIPS-SoC
The SoC for EggMIPS, a superscalar MIPS CPU

### BIOS

We deleted NAND support in PMON2000(BIOS) so the BIOS will load faster.

You can use compiled `gzrom.bin` as BIOS instead.

If you want to compile `pmoncfg` on newer GCC, you should add `-fcommon` in CFLAGS to avoid multiple definition errors.
