**Compiled with Cygwin an Windows 7 32-Bit**

similar to https://elinux.org/Compiling_OpenOCD_for_Windows_7_(LibFTDI)_-_Pre_June_2011

https://sourceforge.net/projects/openocd/ - openocd-0.10.0.zip (newest !)

Compiled with:

````
./configure --enable-remote-bitbang
make CFLAGS=-Wno-error (--> fixes https://sourceforge.net/p/openocd/tickets/190/)
```

TODO: Maybe recompile so we can use USB-Blaster 

```
./configure --enable-usb-blaster --enable-remote-bitbang
```
