# GFN-hotfix

Ultimate Function of Program:

Patch which optimizes GFN, seamlessly, at the runtime of an executable.

How? by automating the following:

- Granting administrator rights to GFN
- Modification of program DPI
- Modification of Dynamic Resolution Scaling
- Enabaling of Direct Mouse Input


The app variation on windows has its issues; namely these are with dynamic
resolution, latency and severe input issues. These can all be mitigated almost 
holistically. With network specs benching from unrecommended to barley passable, I was able
to stream at a quality virtually indistinguishable from native 1080p60fps.

The browser variation of this service allows for more a more 
consistent picture and frame outside of the box, although 
there are major issues with input. Adjusting the mouse's report 
rate to 125 per second fixes this but dosen't account for the visual 
jitter that may occur.

Your obligations:

- run shell
- set mouse report rate to 125 per second (assuming your current rate is 1000c/s 
and your mouse DPI is 3200, set your DPI to 800 to revert the sensitivity)
- Ethernet
- VPN off

GFN->Settings->Streaming Quality:

- Custom => Max bit rate
- Resolution => 1920 x 1080(16:9)
- vsync => ON
- Frame rate => 60 FPS
- Adjust for poor network conditions => OFF
