# GUIA INSTALACIÓN

  >>>   make

  >>>   sudo setenforce permissive

  >>>   sudo insmod 8812au.ko

  >>>   sudo cp 8812au.ko /lib/modules/$(uname -r)/kernel/drivers/net/wireless

  >>>   sudo depmod