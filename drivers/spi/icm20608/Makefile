KERNELDIR := /home/wang/linux/atk-mp1/my_kernel/linux-5.4.31
CURRENT_PATH := $(shell pwd)

obj-m := icm20608.o

build: kernel_modules

kernel_modules:
	$(MAKE) -C $(KERNELDIR) M=$(CURRENT_PATH) modules

clean:
	$(MAKE) -C $(KERNELDIR) M=$(CURRENT_PATH) clean
