#### 文件说明
- flash_image_128k_bl_if_hid.bin = (stm32f103xb_bl.bin + stm32f103xb_stm32f103rb_if_hid.hex)  
    完整的128KB镜像，包括bootloader和interface，为v2.3硬件版本出厂烧录固件
- stm32f103xb_bl.bin  
    bootloader
- stm32f103xb_stm32f103rb_if_bulk.hex  
    支持usb bulk传输的固件，keil目前还不支持，IAR支持。
- stm32f103xb_stm32f103rb_if_hid.hex  
    支持usb hid传输的固件，所有IDE包括keil，iar，openocd均支持。