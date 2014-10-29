Adding the overlay
------------------
To add this overlay to your system:  
uncomment in: `/etc/layman/layman.cfg` the line  
`# overlay_defs : /etc/layman/overlays` to  
`overlay_defs : /etc/layman/overlays`  
and use the following commands  
`wget -P /etc/layman/overlays/ https://raw.github.com/obilx1978/banana-overlay/master/obilx.xml`  
`layman -L`  
`layman -a obilx-banana`

##### All ebuilds into the overlay:  

<table>
<tr><td>
<a href=https://github.com/obilx1978/banana-overlay/blob/master/x11-drivers/xf86-video-sunxifb>x11-drivers/xf86-video-sunxifb</a>
</td><td>
Xorg DDX driver for the devices based on Allwinner A10/A13 SoC
</td></tr>
<tr><td>
<a href=https://github.com/obilx1978/banana-overlay/blob/master/x11-drivers/xf86-video-fbturbo>x11-drivers/xf86-video-fbturbo</a>
</td><td>
Xorg DDX driver for ARM devices (primarily Allwinner A10/A13/A20)
</td></tr>
<tr><td>
<a href=https://github.com/obilx1978/banana-overlay/blob/master/x11-drivers/mali-drivers>x11-drivers/mali-drivers</a>
</td><td>
Symlinks for closed source userspace drivers for Mali 3D graphics accelerator
</td></tr>
<tr><td>
<a href=https://github.com/obilx1978/banana-overlay/blob/master/x11-libs/libdri2>x11-libs/libdri2</a>
</td><td>
Library for the DRI2 extension to the X Window System
</td></tr>
<tr><td>
<a href=https://github.com/obilx1978/banana-overlay/blob/master/x11-libs/libump>x11-libs/libump</a>
</td><td>
Unified Memory Provider userspace code needed for xf86-video-mali
</td></tr>
</table>
