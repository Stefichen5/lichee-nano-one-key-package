Buildroot setup for Lichee Pi Nano
=======================

This script downloads and builds everything needed to run buildroot Linux on your Lichee Pi Nano.

This is a modified version of [xiaoxiaohuixxh's  useful script](https://github.com/xiaoxiaohuixxh/lichee-nano-one-key-package). I adapted it to my needs and fixed some small things that annoyed me, as well as changed the toolchain (since the link to the old one was broken) and updated Kernel and Buildroot.

## Usage

```bash
cd lichee-nano-one-key-package
chmod +x build.sh
./build.sh -m nano_tf
```

You can also specify to just build parts of the system (u_boot, kernel or buildroot) if you don't want to build everything. For that, you use the parameter "-p"

