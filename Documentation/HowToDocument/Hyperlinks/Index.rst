.. include:: ../../../Includes.txt
.. highlight:: rst

======================
Hyperlinks
======================


The complete, anonymous form
============================

This markup will always work. It has a `linktext`, the complete url in `<...>`,
and **two** underscores at the end. **Two** mean that it's an anonymous link. This
means that the `linktext` is NOT added to the internal table of known link definitions::

   `linktext <https://the/complete/url/>`__

Example::

   See `buildinfo <https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-041/_buildinfo/>`__

Result:

See `buildinfo <https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-041/_buildinfo/>`__




A named link
============

Define the linktext `buildinfo` and the url somewhere in the document::

   .. _buildinfo: https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-041/_buildinfo/

Use the defined link as often as you like::

   See the buildinfo_. See the buildinfo_. See the buildinfo_.

Result:

See the buildinfo_. See the buildinfo_. See the buildinfo_.

.. _buildinfo: https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-041/_buildinfo/

tip::

   The url may even be relative::

      .. _buildinfo: _buildinfo



Another way to create a named link
==================================

((to be written))




Anonymous hyperlinks
====================

These may come in very handy especially when you are copying and pasting very long, unhandy links.
Here we use some nice links for demonstration.
Create a list with anonymous target urls. To do so, start the line with **two** underscores and
a blank and then paste the link. Afterwards in your text you can use - and consume - one
link after the other in exactly the order you listed them. Example::

   __ https://typo3.org/
   __ https://typo3.org/extensions/repository/
   __ https://docs.typo3.org/

   Go here__ first, then look at `the extensions`__ and don't forget to visit
   the documentation__.

Result:

__ https://typo3.org/
__ https://typo3.org/extensions/repository/
__ https://docs.typo3.org/

Go here__ first, then look at `the extensions`__ and don't forget to visit
the documentation__.



