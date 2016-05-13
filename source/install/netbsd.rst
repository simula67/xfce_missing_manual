Installing Xfce 4.12 on NetBSD
==============================

From binaries:
--------------

  # pkgin -y in xfce4 xfce4-extras 
  
  or
  
  
  # pkg\_add xfce4 xfce4-extras

From `pkgsrc <http://pkgsrc.org/>`__ (source package manager for NetBSD and others):
------------------------------------------------------------------------------------

  # cd /usr/pkgsrc/meta-pkg/xfce4
  
  # make install clean
  
  # cd /usr/pkgsrc/meta-pkg/xfce4-extras
  
  # make install clean

Besides the meta packages, there are more xfce applications, panel
plugins, thunar plugins you can install, see the `List of xfce packages
in pkgsrc <http://pkgsrc.se/search.php?so=xfce4>`__. `More information
on xfce packages for pkgsrc <https://wiki.netbsd.org/xfce4/>`__
