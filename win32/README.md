**Compiled with Cygwin an Windows 7 32-Bit**

Similar to: https://elinux.org/Compiling_OpenOCD_for_Windows_7_(LibFTDI)_-_Pre_June_2011 
but without the extra libusb stuff ...

Source Code used: https://sourceforge.net/projects/openocd/ - openocd-0.10.0.zip (newest !)

Compiled with:

```
./configure --enable-remote-bitbang
make CFLAGS=-Wno-error // fixes: https://sourceforge.net/p/openocd/tickets/190/
```

--> To flash just run **openocd.exe** (specify your own .svf file in openocd.cfg) <--

**Works !!!** (only these files needed ...)
