# ApricotOS

##Bootloader
Updated the bootloader by amnually adding the seggmentation. The system can automatically load the bootloader into any address in the memory. this causes issues while switiching over differnet devices.
Hence addign a manual segmentation model forces the system to laod the bootloader into a specific address (Here : 0x7c00), allowing better control over the process (Here printing "Hello World").
![Screenshot from 2023-11-28 04-28-49](https://github.com/abid-sayyad/ApricotOS/assets/49099853/ad4777c8-b360-4af9-a4bc-830c06bb16c6)
![Screenshot from 2023-11-28 04-29-05](https://github.com/abid-sayyad/ApricotOS/assets/49099853/33f11404-528e-4502-a99c-95f8e9513441)
