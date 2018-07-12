.. include:: ../../Includes.txt


.. _drafts-visually-structure:

================================================
DRAFTS for visually structuring things on a page
================================================

Test out and showcase some ideas.

Adresses `PR for contribution guide
<https://github.com/TYPO3-Documentation/TYPO3CMS-Guide-ContributionWorkflow/issues/77>`__

* **Problem 1: Too much information on page.** Especially if there are several
  steps to perform and images, notes and hints are on the page, it it difficult
  to see at first glance where one step ends and the next one begins.

   * Solution: Use one of the methods with numbering and background color,
     e.g. `rst-class:: bignums``
   * Solution: Use the normal section headers in a consistent way
   * Solution: Do not use too many `.. _tip::` or `.. _hint::`. Use sidebar
     instead. Only use tip / hint etc. on top of page?
   * Solution: use a box-shadow for images, possibly add transparent border inside image

* **Problem 2: Images containing text do not stand out enough from plain text**

   * Solution: Use `box-shadow` or `with-border` for images, add additional
     white border in image when creating it.

* **Problem 3: On wide screens, width of area for text is too wide.**
  This makes it hard to read. Example: `A journey through the blog example
  <https://docs.typo3.org/typo3cms/ExtbaseFluidBook/3-BlogExample/1-first-orientation.html>`__

   * Solution: See `issue #83 in t3SphinxThemeRtd <https://github.com/TYPO3-Documentation/t3SphinxThemeRtd/issues/83>`__


**General best practices:**

* don't create long paragraphs
* use images and tips / hints etc. sparingly
* very sparingly use bold to emphasize important things (helps when people scan page)
* don't put too much on one page
* always use visual styling consistently for specific type of content,
  e.g. only use sidebars to link to additional information. Use this
  consistently within a manual and preferably within the entire docs.



.. toctree::
   :maxdepth: 1
   :glob:

Method 01: 1-2-3 with big numbers xxl
=====================================


first found in form extension docs: https://docs.typo3.org/typo3cms/extensions/form/QuickStart/Index.html

.. rst-class:: bignums-xxl

1. pro

   * good division between parts
   * numbering makes it easier to follow

2. con

   * not in menu, so you can't jump to specific section from menu
   * no named anchor so you can't link directly to section
   * less contrast here because of background color


3. conlusion

   **Good method if there are not too many items (up to 5 is ok).
   It is probably a good idea to use this consistently throughout
   the documentation**


Method 02: 1-2-3 with big numbers
=================================

.. rst-class:: bignums

1. pro

   * good division between parts
   * numbering makes it easier to follow

2. con

   * not in menu, so you can't jump to specific section from menu
   * no named anchor so you can't link directly to section

3. conlusion

   **Good method if there are not too many items (up to 5 is ok).
   It is probably a good idea to use this consistently throughout
   the documentation, e.g. for a Quick start section**





Method 03: subsections
======================

pro:
----

* division between subsection
* subsection title in menu so you can click directly
* you can link directly to section with named anchors


con:
----

* no numbering





Method 04: subsections with numbering
=====================================

step 1 : show the advantages
----------------------------

* division between subsection
* subsection title in menu so you can click directly
* you can link directly to section with named anchors

step 2: show the disadvantages
------------------------------

* the division between the steps is not as clear as with
  the number method above






Methods 05 : Borders for images
===============================


Adresses problem that it is difficult to distinguish images from text.


For demo with images, also see: https://docs.typo3.org/typo3cms/drafts/github/TYPO3-Documentation/t3SphinxThemeRtdDemoDocs/ImagesAndFigures/Index.html


Default
-------

.. figure:: _assets/gerrit_signin.png


With drop-shadow
----------------

.. figure:: _assets/gerrit_signin.png
   :class: with-shadow


sfsf sfdsfs sfsf sfdsfs sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd


sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs xdxvss sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsf aAsfsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfs.

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

With border
-----------

.. figure:: _assets/gerrit_signin.png
   :class: with-border


sfsf sfdsfs sfsf sfdsfs sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd


sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs xdxvss sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsf aAsfsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfs.

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

With border
-----------


sfsf sfdsfs sfsf sfdsfs sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd


sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs xdxvss sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsf aAsfsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfs.

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

.. figure:: _assets/gerrit_signin.png
   :class: with-panel

sfsf sfdsfs sfsf sfdsfs sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd


sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs xdxvss sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsf aAsfsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfs.

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd


With width and alignment (left)
-------------------------------

sfsf sfdsfs sfsf sfdsfs sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd


sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs xdxvss sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsf aAsfsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfs.

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

.. figure:: _assets/gerrit_signin.png
   :width: 200px
   :align: left
   :height: 100px
   :figclass: align-left


sfsf sfdsfs sfsf sfdsfs sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd


sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs xdxvss sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsf aAsfsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfs.

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd

sfsf sfdsfs sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfds sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd
sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd sdfsfsdfsd  sdfdsfs sdfdsfdsfds sdfssd




