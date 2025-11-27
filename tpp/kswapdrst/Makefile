obj-m   := kswapdrst.o
KDIR    := /lib/modules/6.3.0-colloid/build
PWD := $(shell pwd) 
  
all: 
		$(MAKE) CC=gcc-13 -C $(KDIR) M=${PWD} SUBDIRS=$(PWD) modules

clean:
		rm -f *.ko *.o *.mod *.mod.c modules.order Module.symvers test
