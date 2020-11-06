# Cross Compiler workspace

The original PKGBUILD files are referenced from this [repository](https://github.com/tavianator/arch-rpi-cross), Or the [AUR](https://aur.archlinux.org/packages/arm-linux-gnueabihf-gcc/) packages.

See the *contributor* list and *maintainer* list at each PKGBUILD for full credit list.

## A. Installation sequence

One should install the packages like this:

1. `arm-linux-gnueabi-binutils`
2. `arm-linux-gnueabi-gcc-stage1`
3. `arm-linux-gnueabi-linux-api-headers`
4. `arm-linux-gnueabi-glibc-headers`
5. `arm-linux-gnueabi-gcc-stage2`
6. `arm-linux-gnueabi-glibc`
7. `arm-linux-gnueabi-gcc`

See the AUR page above for more information

## B. Automated scripts

The automated script is copied and slightly modified from the git repository mentioned
above.

```
./install.sh
```


