# D-link-dwa-182-rev-D1-linux-drivers

Download offical drivers
https://support.dlink.com/ProductInfo.aspx?m=DWA-182

add this to Makefile 
EXTRA_CFLAGS += -Wno-error=date-time

make && make install

Works on Kernel 5.5 - and probably 5.7 too

RTL88x2BU
Realtek AC-1300 MiMo drivers
linux 
