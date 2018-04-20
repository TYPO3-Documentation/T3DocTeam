.. include:: ../../Includes.txt
.. highlight:: shell


This builds on the already existing section
:ref:`Reporting a bug <t3contrib:bugreporting-index>` existing docs but
focuses on what should go in the title and description of a bug report
(e.g. clear title, steps to reproduce).


.. important::
   First see which target group is to be handled. The contrib guide is for
   core developers. Do we need an extra section for people reporting bugs
   who may not be developers? Should this be here or somewhere else?
   Is it necessary to provide more information
   for writing a good bug report?

==============================
How to write a good bug report
==============================

Title
=====

Keep it short and descriptive
-----------------------------

Try to write a title that is not too long, but contains enough information
in order for people to get a good idea what might be the problem.

Also, remember that people might browse through the titles in listings
and search results. The first and only thing they see is the title. Judging
from the title, they must decide, whether to look at the bug report

Reasons people may do this are:
* Someone wants to report a bug and is looking for similar bug reports. With
  only vague titles they would have to click on each and every one in order
  to read the description.
* A core developer wants to work on a specific bug and is looking for related
  bugs


Examples of titles
------------------

"Bug in Backend"
~~~~~~~~~~~~~~~~

**Much too vague.** A better title might be for example: "Moving pages in the
pagetree fails with Drag'n'drop".


Description
===========

The description might contain the following

* Short, concise description of problem
* System information (e.g. TYPO3 version), which browser *if* this is relevant to the bug
* Steps to reproduce
* Expected result
* Actual result
* Additional information such as log entries, exception dumps, screenshots or videos of
  reproducing the problem

In general: Keep it as short as possible. Use formatting to seperate the sections. For
example is one part is a bug report but another part is a suggested solution, use headings
for this.

Make it as easy as possible for someone glancing through your bug report.
