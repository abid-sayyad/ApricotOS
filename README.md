# ApricotOS

## Bootloader
Updated the bootloader by manually adding the segmentation. The system can automatically load the bootloader into any address in the memory. this causes issues while switching over different devices.
Hence adding a manual segmentation model forces the system to load the bootloader into a specific address (Here: 0x7c00), allowing better control over the process (Here printing "Hello World").
![Screenshot from 2023-11-28 04-28-49](https://github.com/abid-sayyad/ApricotOS/assets/49099853/ad4777c8-b360-4af9-a4bc-830c06bb16c6)
![Screenshot from 2023-11-28 04-29-05](https://github.com/abid-sayyad/ApricotOS/assets/49099853/33f11404-528e-4502-a99c-95f8e9513441)

### Interrupt
Implemented own interrupt using Interrupt Vector Table that prints "A", whenever invoked. Defined int 0, by changing the address it points to.
![Screenshot from 2023-11-29 13-14-58](https://github.com/abid-sayyad/ApricotOS/assets/49099853/3a0e11a5-2286-4330-ac6a-b95b6add951f)


Also added interrupt '1', which prints "V" when invoked.
