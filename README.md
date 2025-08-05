USBKVM
======

You know this? Your home server won't ping anymore and now you gotta 
get a monitor and a 
Since I was too lazy to figure out how to properly capture the mouse to 
emit relative movements, USBKVM emulates an absolute pointing s projects, I can't recommend tinyusb enough. It's 
really good as far as anything involving USB goes.

On the other end, it implements an I²C peripheral to receive commands 
from the MS2109. After some fiddling, I got it to work reliably 
without clock stretching since I don't think the MS2109 supports that. 
One side-effect of ted by one single 
firmware image. To tell them apart, pin PB8 is grounded on USBKVM Pro 
and floating on USBKVM.

## Firmware updates

TL;DR: Don't worry about it, the client app automatically does the right thing.

The first 8k of the 
