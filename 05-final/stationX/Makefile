obj-m +=spark_m.o

all:
    make ARCH=arm CROSS_COMPILE=arm-linux-gnueabi- -C /home/felix/Documents/develop/kbuild/linux M=$(PWD) modules
clean:
    make ARCH=arm CROSS_COMPILE=arm-linux-gnueabi- -C /home/felix/Documents/develop/kbuild/linux M=$(PWD) clean
