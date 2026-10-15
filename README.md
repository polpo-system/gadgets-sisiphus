# gadgets-sisiphus

Sisiphus for the gadgets of [polpo](https://github.com/polpo-system/polpo): a small animated gadget
of Sisyphus rolling his stone, over and over.

```
portia.Install gadgets-sisiphus
```

## Using

    Gadgets.Insert Sisiphus.New ~    the animation at the caret

## What is here

    src/Sisiphus.Mod        the gadget
    share/Sisyphus.Data     the pictures of the animation
    tools/Sisiphus.Tool
    test/SisiphusTest.Mod

The source comes from ETH Linux Oberon (OLR, 2017-06-18), converted from an Oberon text to plain
text; the first commit has it unchanged. It compiles unchanged with all five of polpo's compilers
(x86, ARM, ARMv7, RISC-V, MIPS).

## Tests

    SisiphusTest.Run      1 check: the gadget made; it needs the desktop's display

The license is GPL-3 (`LICENSE`); the code comes from ETH Oberon, whose license (`LICENSE.ETH`)
asks to keep its copyright notice and conditions, which `LICENSE.ETH` does.
