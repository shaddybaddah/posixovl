Installation when using a Git snapshot
======================================

Requirements:

* autoconf
* automake
* plus any requirements specified for building from tarballs

Commands for building:

.. code-block:: sh

	./autogen.sh
	# and now, follow the commands specified for tarballs


Installation when using a tarball
=================================

Requirements:

* a C compiler
* fuse-devel >= 2.6.5
* libattr-devel

Commands for building:

.. code-block:: sh

	mkdir obj
	cd obj
	../configure
	make
