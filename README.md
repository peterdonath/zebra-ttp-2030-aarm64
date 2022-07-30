# zebra-ttp-2030-aarm64
Zebra ttp 2030 on Raspberry 4

By default Zebra only provides drivers for Windows systems.

In theory CUPS 1.6 has these kind of KPL kiosk printers, but they does not.

I will include both filter and ppd files for multiple systems to save you hours of agony.


Finally I decided to go direct printing in Vendor mode

In Zebra toolbox

<ESC>&P<59>1 sets the vendor mode

<ESC>&<4> stores it in flash

Only root can print :(
