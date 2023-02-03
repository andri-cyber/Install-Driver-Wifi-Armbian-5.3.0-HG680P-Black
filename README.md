# Install-Driver-Wifi-Armbian-5.3.0-HG680P-Black

How to install

    sudo cp rtl8189fs.ko /lib/modules/5.3.0-aml-g12/kernel/drivers/net/wireless/

    sudo /sbin/depmod -a

    sudo modprobe rtl8189fs
