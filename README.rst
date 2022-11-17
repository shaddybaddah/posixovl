The POSIX Overlay Filesystem
============================

posixovl provides a filesystem view that supports various POSIX operations
while using an otherwise incapable lower filesystem. Filesystems of various
degrees of POSIXness can be utilitzed. VFAT is a common denominator when it
comes to cross-compatibility, though NTFS — its features are unused in Linux —
would be another possibility. Native POSIX-capable filesystems can be used too,
though that seems like an unusual application of posixovl.

* `Installation instructions <INSTALL.rst>`_
* Runtime use is described in a manpage. Use `man -l posixovl.1` to view
  (or `man posixovl` when using a distro-supplied pre-built package).
