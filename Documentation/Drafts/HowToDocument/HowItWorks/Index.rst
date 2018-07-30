.. include:: ../Includes.txt
.. highlight:: rst


.. _how-it-works:

============
How it works
============

Here, we explain some of the basics. In the next chapter, we will
walk you through how to make changes in the documentation step by step.

ReST
====

The files used within the documentation are in ReST (Restructured Text)
format, which means they are basically text files with some markup for
bold, headers, links etc., similar to what is used in Wikis.

These files will be converted into a final format which can be displayed
online or downloaded. The formats we currently use are HTML and PDF.
The conversion process is referred to as "rendering".

Github
======

All documentation files for one manual are included inside a git repository
on Github.

You can make the changes either directly on Github using the Github
user interface or use a local git workflow.

Pull Requests
=============

In either case you will make the changes and propose them as a Pull
Request. That means, your changes will not immediately be merged
into the main repository. They must be reviewed and merged by one
of the maintainers first.

Editing workflow
================

Making changes basically consists of these steps:


.. t3-field-list-table::
 :header-rows: 1

 - :Step:         Step
   :Who:          Who

 - :Step:         1. Edit the file(s)
   :Who:          You

 - :Step:         2. Preview
   :Who:          You

 - :Step:         3. Create a commit (Saving)
   :Who:          You

 - :Step:         4. Create Pull Request (Proposing Changes)
   :Who:          You

 - :Step:         5. Merge Pull Request (Accepting Changes)
   :Who:          Maintainer

 - :Step:         6. Update result on docs.typo3.org
   :Who:          Automatic

