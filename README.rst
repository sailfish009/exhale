exhale
========================================================================================

Automatic C++ library api documentation generation: breathe doxygen in and exhale it out.

Brief
----------------------------------------------------------------------------------------

This project attempts to port the Doxygen style Class and File hierarchies into Sphinx,
using Breathe to pull in the documentation from Doxygen.  This project was developed
with C++ in mind, but would likely also work well for a pure C library as well.

Full documentation and usage guide: |docs|

.. |docs| image:: https://readthedocs.org/projects/exhale/badge/?version=latest
    :alt: Documentation Status
    :scale: 100%
    :target: https://exhale.readthedocs.io/en/latest/?badge=latest

Participate
----------------------------------------------------------------------------------------

If you find a problem or think there is something that should change, please submit an
issue (or pull request!) explaining what should change.  I made this because it was
something I really wanted, and felt the community at large could benefit from as well.
I put a lot of effort into making it flexible, but it is by no means perfect.

Credit
----------------------------------------------------------------------------------------

This project could not exist without the already excellent tools available: Doxygen,
Sphinx, Breathe, and many others.  In particular, though, **all** files in the
``treeView/_static`` directory were scraped from Stephen Morley's collapsibleLists_
thanks to his generous license_.  I make no claims to these files, and only host them
here out of convenience for you.

.. _collapsibleLists: http://code.stephenmorley.org/javascript/collapsible-lists/
.. _license: http://code.stephenmorley.org/about-this-site/copyright/

License
----------------------------------------------------------------------------------------

This project uses a BSD 3-clause license, listed at the top of ``exhale.py``, in hopes
that it will be accessible to most projects.  If you require a different license, please
raise an issue and I will consider a dual license.
