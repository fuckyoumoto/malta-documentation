# BROM

BROM (Boot ROM) - embedded bootloader in MediaTek (MTK) chips, which is launched first when the device is turned on. 

It is responsible for initial system initialization and allows firmware upload via COM port.

:::info
Since this phone was not released after 2022, BROM is still available in it.<br />
[More info](https://github.com/melontini/bootloader-unlock-wall-of-shame/blob/main/brands/motorola/README.md)
:::

## Boot to BROM mode
- Power off phone
- Hold the **Google Assistant** and **Power** buttons, then connect your phone to the PC
- The phone will go into BROM mode, but if no data is sent via specialized tools within 3 seconds, the COM port will be closed