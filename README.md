#  MaxiCam lvgl8 demo 
(modified from duo-lvgl-fb-demo)

enable the framebuffer display on your Maxicam
https://wiki.sipeed.com/hardware/en/lichee/RV_Nano/5_peripheral.html

If you want to use the framebuffer function, create a file named fb in the first partition of the sd card:

touch /boot/fb

lv_port_linux_frame_buffer from:
```
git clone [[https://gitcode.com/lvgl/lv_port_linux_frame_buffer.git](https://github.com/Milk-V-Meshtastic/duo-lvgl-fb-demo)](https://github.com/Milk-V-Meshtastic/duo-lvgl-fb-demo)
cd lv_port_linux_frame_buffer
git submodule update --init --recursive
```

