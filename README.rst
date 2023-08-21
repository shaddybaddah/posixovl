The POSIX Overlay Filesystem
============================

posixovl provides a filesystem view that adds various POSIX operations atop
lower filesystems that may lack such. VFAT is a common denominator when it
comes to cross-compatibility, though NTFS — its features are unused in Linux —
would be another possibility. Native POSIX-capable filesystems can be used too,
though that seems like an unusual application of posixovl.

* `Installation instructions <INSTALL.rst>`_
* Runtime use is described in a manpage. Use `man -l posixovl.1` to view
  (or `man posixovl` when using a distro-supplied pre-built package).

POSIX features provided:

* Ownership and modes
* Extended file attributes
* Hardlinks, special file types

Features (POSIX or otherwise) not explicitly provided by this layer:

* O_TMPFILE
* Locking
* Absolute atomicity
