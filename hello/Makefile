obj-m := hello.o

PWD = $(shell pwd)
KDIR = /lib/modules/4.2.0-27-generic/build

all:
	$(MAKE) -C $(KDIR) M=$(PWD)

.PHONY: clean
clean:
	rm -f *.mod.c *.mod.o *.o *.ko *.order *.symvers *.tmp_versions *.cmd
