In general
==========

Some Linux distributions have posixovl already available. Use their package
management system if you can. `Repology
<https://repology.org/project/posixovl/versions>`_ is an aggregation page that
summarizes who has got what.


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
