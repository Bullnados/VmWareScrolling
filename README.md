# VmWareScrolling
Scroll vertical in workstatation (tested with 11.0) and player (untested) 
Following text is just c&c from https://bitbucket.org/DouglasCameron/windows-trackpad-scroller-for-vmware/overview
All files are also made by Douglas Cameron!!


This program enables use of a trackpad in a VMWare virtual 
machine under a Windows host.

To run, execute VMWareTrackpadScroller.exe after starting 
VMWare Workstation or Player and respond to the two dialog
boxes.

The program supports VMWare Workstation and Player.
The program supports starting and stopping the drivers.

The executable can be found under 'Downloads'.

Notes:
- If VMWare is used in multi-monitor mode, it may be necessary 
  to start this program after switching to dual monitor mode.
- Don't move the executable or hook.dll after scrolling is enabled.
- This program may need to be restarted when mouse drivers added.
  
Comments:
  An alternative to this program is multiswipe.com which has far 
  more capability. However, it must be granted full permissions 
  (certificate authority) to operate, which I was hesitant to grant
  without seeing the source code.
  
  It can be difficult to find the Visual Studio 2010 C runtime for 
  the original so this is compiled in VS2012 and with improvements 
  and dependencies.

This program is a derivation of Andrew Zabavnikov's code, built on 
Anthony Prieur's code (anthony.prieur@gmail.com), which is described:

 http://superuser.com/questions/131297/use-synaptics-touchpad-scroll-in-vmware-guest/683726#683726
 
and found here:

 https://github.com/devpack/vmware-synaptics-touchpad-scroll
 
  In particular it is based on Commit eae912f2cb circa 2013.

For discussions, see
 http://superuser.com/questions/131297/use-synaptics-touchpad-scroll-in-vmware-guest/683726#683726
and
 https://communities.vmware.com/thread/430105
  
  
This is compiled with Visual Studio 2012.
