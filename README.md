# tutorial-dependence-on-mesa-and-their-building-example-configure
tutorial  dependence on mesa and their building example configure

Example libglu-mesa

./configure --prefix=/usr --exec_prefix= --libdir=/lib/x86_64-linux-gnu --includedir=/include --disable-static

----------------------------------------------------------------------------------------------------------------------

Example dri

./configure --prefix=/usr --exec_prefix= --libdir=/lib/x86_64-linux-gnu --includedir=/include --dridriverdir=/usr/lib/x86_64-linux-gnu/dri

-------------------------------------------------------------------------------------------------------------------

Example egl , gl , glesv2 , libdrm , libdrm_amdgpu , libdrm_intel , libdrm_nouveau , libdrm_radeon , wayland-cursor , wayland-egl.pc , xcb , x11 , x11-xcb , xau (xproto) , xcb-dri2 , xcb-dri3 , xcb-glx , xcb-present , xcb-randr , xcb-render , xcb-shape , xcb-sync , xcb-xfixes , xdamage (xproto damageproto) , xdmcp (X Display Manager Control Protocol library) , xext (Misc X Extension Library) , xfixes (xproto fixesproto >=<version> , xxf86vm.

variant 1)

./configure --prefix=/usr --exec_prefix= --libdir=/lib/x86_64-linux-gnu --includedir=/include

Variant 2)

./configure --prefix=/usr --exec_prefix= --libdir=/lib/x86_64-linux-gnu --includedir=/include --disable-static


--------------------------------------------------------------------------------------------------------------------

wayland-client , wayland-server

./configure --prefix=/usr --exec_prefix= --datarootdir=${prefix}/share --pkgdatadir=${datarootdir}/wayland --libdir=/lib/x86_64-linux-gnu --includedir=/include

------------------------------------------------------------------------------------------------------------------------------

wayland-scanner

./configure --prefix=/usr --exec_prefix= --datarootdir=${prefix}/share --pkgdatadir=${datarootdir}/wayland wayland_scanner=${exec_prefix}/bin/wayland-scanner

----------------------------------------------------------------------------------------------------------------------------





