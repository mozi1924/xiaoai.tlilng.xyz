# mtkclient brush machine, backup, unlock tutorial

## This tutorial is written by [mozi1924](http://www.coolapk.com/u/8793429)

------------------------------

># Prepare in advance

device to flash

data line

mtkclient software (mtkclient2.0 tool is recommended)

usbdk driver

---------

1. First install usbdk, go to usbdk[official warehouse](https://github.com/daynix/UsbDk/releases) to download

If you can't connect, you can download it from the driver folder on the home page of the website.

When downloading you will see these two versions:

<img decoding="usbdk" src="../d/.picture/usbdk.png" width=300px>

Choose the version that suits your computer. If your computer processor is 32-bit, choose x86, and if your computer processor is 64-bit, choose x64.

After downloading, install and restart
> # 1. connect

open software

Connect the data cable to the computer

> To connect speakers:

>Small screen device

Press and hold the top three keys and insert the data cable, as shown below:

<img decoding="lx04threebutton" src="../d/.picture/lx04threebutton.png" width="50%">

> Large screen equipment

The large-screen device has a large power and has an independent power supply, so the micro-usb is hidden, and you will see the micro-usb interface when you open the bottom rubber pad, as shown in the figure:

<img decoding="microusb" src="../d/.picture/microusb.png" width="500px">

Insert the data cable, then press and hold the three buttons to connect the power

After the connection is successful, the software interface is as shown in the figure:

<img decoding="mtkclient" src="../d/.picture/mtkclient.png" width="500px">

----

> # 2. Flash
Enter the write partition, as shown in the figure:

<img decoding="write" src="../d/.picture/write.png" width="500px">

Click Select from Directory, select the uncompressed backup package, and then click Write Partition. After the progress bar is finished, you can power off and restart.

> # 2. Backup

Enter the reading partition, click to select all partitions, then click the reading partition next to it, select a directory to save, and wait until the article is finished

> # 3. Unlock

Enter the flash tool page, as shown in the figure:

<img decoding="mtkclientflashtool" src="../d/.picture/mtkclientflashtool.png" width="500px">

Click the unlock bootloader below and wait for the progress bar to run (usually it is completed instantly)