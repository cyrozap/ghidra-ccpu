# MediaTek CCPU (GCPU) Processor Module for Ghidra

**NOTE**: This is a work-in-progress. Most instructions are supported, but
many of them have not been tested on real hardware. Because of this, the
decompiler output for those untested instructions may be incorrect.

## Build and Install

```
$ git clone https://github.com/cyrozap/ghidra-ccpu.git
$ cd ghidra-ccpu
$ gradle
```

The `dist` directory will now contain the extension zip file that you can
install into Ghidra.
