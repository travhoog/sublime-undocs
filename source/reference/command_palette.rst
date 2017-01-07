===============
Command Palette
===============

The command palette is fed entries with ``.sublime-commands`` files.


File Format of ``.sublime-commands`` Files
==========================================

.. include:: /_includes/command_palette_summary_table.g.txt


Example
=======

.. include:: ../common/command-palette-example-0.txt

.. _Command Palette Item:


Command Palette Item
====================

These are the elements
that can be included
in a ``.sublime-commands`` item:

``caption``
   Text for display in the command palette.

``command``
   Command to be executed.

``args``
   Arguments to pass to ``command``. Note that to locate the packages folder
   you need to use a snippet-like variable: ``${packages}`` or ``$packages``. This
   differs from other areas of the editor due to different implementations in
   the lower layers.


How to Use the Command Palette
==============================

#. Press :kbd:`Ctrl+Shift+P' (or :kbd:`Command+Shift+P' on a Mac)
#. Select command

Entries are filtered by current context. Not all entries will be visible at all
times.
