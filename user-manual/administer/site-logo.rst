.. _site-logo:

=========
Site logo
=========

In AtoM, the site logo is the graphic that appears at the top of all pages in
the left-hand corner of the :term:`header bar`. Clicking on the logo will take
the user to the :term:`home page`.

AtoM ships with a default logo that can only be replaced by a System
Administrator (i.e. someone who has access to the the AtoM application files on
your web server): to do this, replace the file **images/logo.png** in the AtoM
root directory with the logo for you site. The logo file must be in "Portable
Network Graphics" (`PNG
<http://en.wikipedia.org/wiki/Portable_Network_Graphics>`__) format and it must
be called "logo.png".

It is important to note that the **maximum height** recommendation for a logo
in AtoM for a logo is **50px**. An image or icon exceeding 50px will break the
page layout, unless a developer has altered the theme of the page.

.. |gears| image:: images/gears.png
   :height: 18
   :width: 18

.. TIP::

   Users who do **not** wish to have a logo can remove it by clicking on the
   |gears| :ref:`Admin <main-menu-admin>` menu in the :term:`main menu` located
   in the :term:`header bar` and selecting "Settings" from the
   :term:`drop-down menu`. Scroll down to the "Default page elements" and
   unselect the "Logo" value. This will remove the AtoM logo (or your own logo)
   from the AtoM header bar. For more information, see :ref:`Settings`.

For more information on themes and general page settings, see :ref:`navigate`,
:ref:`settings`, :ref:`themes`, or :ref:`archival-descriptions`.

:ref:`Back to top <site-logo>`
