Installation
==============

Alvis requires Java to run, and a LaTeX compiler to create PDFs from the tex files that Alvis produces, or a browser to view the svg files that Alvis produces. First, download the repository from https://github.com/SR-Martin/alvis.git.

A jar file is included in the repository, and is all that is necessary to run Alvis. This can be found at ``/path/to/Alvis/dist/Alvis.jar``, usage instructions are in the :doc:`usage` section.

If you wish to compile Alvis yourself, you may do so using the file ``build.xml`` found in the Alvis root directory, and `ant <http://ant.apache.org/>`_, as follows. In the terminal, type::

	cd /path/to/Alvis/
	ant compile jar

Then, to run Alvis::

	cd dist
	Java -jar Alvis.jar


You can also build a linux executable directly (thanks to `rsuchecki
<http://github.com/rsuchecki>`_ for providing this functionality)::

	cd /path/to/Alvis/
	ant linux-bin
