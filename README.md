# termux-unison
Workaround for termux-unison.


unison-aarch64-u20.04-v2.48.4-4.tgz
--

ISSUES
------
 - only for ubuntu 20.04 (2.48.4-4)
 - incompatible with ubuntu 18.04 (2.48.4) version
 - ignorearchives flag is required on stock android 10
 - overwrites ~/.unison/default.prf


INSTALL
-------
 scp unison-aarch64-u20.04-v2.48.4-4.tgz phone-name:  
 ssh phone-name  
 cd ..  
 tar xzf home/unison-aarch64-u20.04-v2.48.4-4.tgz  
 unison  

ABOUT
-----
  It's patchelf-ed wrapper for unison from proot-distro Ubuntu 20.04.2.  
  Doesn't need proot-distro. Minimal standalone version.  
    
  
!!! NOT TESTED YET !!!
----------------------
