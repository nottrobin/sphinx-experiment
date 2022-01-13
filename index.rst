=================
All about my work
=================

.. toctree::
   :maxdepth: 1

   successful-projects
   unsuccessful-projects

Hardware
========

.. sidebar:: This is a sidebar

    This is the body of the sidebar.

**This strongly-emphasised text** will usually appears in bold. *Emphasis*
usually appears in italics.

* item
* item


Software
========

The list of links below appears in a ``seealso`` directive.

.. seealso::

    * `Example <https://example.com>`_
    * `Python <https://python.org>`_


Firmware
========

Sphinx has a number of parsers for automated language highlighting in
code-blocks. It does a good job of guessing what language you're using,
but you can also state that explicitly.

.. code-block:: bash
   :emphasize-lines: 2-3

    python3 -m venv sphinxenv
    source sphinxenv/bin/activate
    pip install sphinx
    pip freeze > requirements.txt
    sphinx-quickstart
