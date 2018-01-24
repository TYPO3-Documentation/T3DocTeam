.. include:: ../../Includes.txt


==============================
To be done
==============================

What the T3DocTeam should be tackling

.. contents:: What needs to be done?!
   :depth: 2
   :local:
   :backlinks: top
   :class: compactlist


Tasks to be done regularly
==========================

Check and process open issues
-----------------------------

Check whether there are open issues for the official manuals and solve them, like

- https://github.com/TYPO3-Documentation/TYPO3CMS-Reference-TCA/issues
- https://github.com/TYPO3-Documentation/TYPO3CMS-Reference-CoreApi/issues
- https://github.com/TYPO3-Documentation/TYPO3CMS-Reference-FileAbstractionLayer/issues
- ...


Process Pull Requests
---------------------

Are there open pull requests?
Observe https://docs.typo3.org/services/GithubPullRequests/
Become a watcher of the repositories of the official manuals at https://github.com/TYPO3-Documentation


Move documentation
==================

Find out what documentation should be moved. Check:

-  `TYPO3.org <https://typo3.org/>`__: We need a list: What needs to be done?

   | ➊ snippets?
   | ➋ ...

-  `TYPO3 wiki <https://wiki.typo3.org/>`__: We need a list: What needs to be done?

   | ➊ Harry Glatz has already noted `some ideas
     <https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-003/>`__
   | ➋ Release notes like `this one <https://wiki.typo3.org/TYPO3_CMS_7.6.14>`__



Making Documentation available
==============================

Unsorted tasks
--------------

-  Continue with the "Render Documentation Guide" https://docs.typo3.org/typo3cms/RenderTYPO3DocumentationGuide/
-  Continue with "rst-ing with PhpStorm" https://docs.typo3.org/typo3cms/drafts/github/wmdbsystems/RSTingWithPhpStormGuide/
-  Continue with https://docs.typo3.org/typo3cms/drafts/github/wmdbsystems/TYPO3ComposerGuide/
-  Q: How do I set up PhpStorm for reST? A: See the `answer (with screenshots) at
   <https://github.com/T3DocumentationStarter/Public-Info-015/issues/1>`__

-  Ask about chapter "Community Writings" (`Tweet <https://twitter.com/marantern/status/798127207306723328>`__)


Extensions Advisor
------------------

((idea for a topic at docs.typo3.org))


Extensions - and what their developers and the community says.

ext:devlog
~~~~~~~~~~

2016-11-14 by François Suter at `Forge <https://forge.typo3.org/news/810>`__:

   Version 3.0 released and moved to GitHub

   The road to devlog version 3.0 has been long and bumpy indeed. Years ago Fabien Udriot
   started a brand new version for TYPO3 4.5, using ExtJS for the backend module. The work
   was never finished and ExtJS fell from grace. The project lay dormant for a couple of years.
   Then an attempt was made to base the devlog on TYPO3's logging API, but this also faltered along the way.

   About last year I finally found the motivation to give the project yet another fresh start.
   Alternating sprints and breaks, the new version was eventually ready. It is entirely rewritten,
   with a squeaky clean code base. The backend module relies on jQuery and DataTables for paginating,
   searching and filtering. The "Clear log entries" feature is now available from a convenient drop-down.

   The devlog also now uses a concept of log writers, which makes it possible to route devlog
   calls to different outputs/storages. By default, the extension provides a database and a file writer.

   Last but not least, I moved the extension to GitHub. Hopefully this will help people contribute and
   maybe also shift ownership to someone else, as I don't feel like continuing to maintain this extension.
   New home: https://github.com/fsuter/devlog




How to do documentation with Github
-----------------------------------

These Q & A are especially important in the context of working with the
`T3DocumentationStarter projects <https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-001/TeachingDocs/StarterManuals/Index.html>`__.

#. `How do I create a folder? <https://github.com/T3DocumentationStarter/Public-Info-001/issues/2>`__
#. `How can I rename a folder? <https://github.com/T3DocumentationStarter/Public-Info-001/issues/3>`__
#. `SSH doesn't work with my T3DocumentationStarter project
   <https://github.com/T3DocumentationStarter/Public-Info-015/issues/1>`__
#. `How often will and when are manuals being updated on our docs.typo3.org server?
   <https://github.com/T3DocumentationStarter/Public-Info-001/issues/4>`__


Can we make use of Gists?
-------------------------

Example Gist:
`ActionViewhelper by Xavier, 2016-11-15 <https://gist.github.com/xperseguers/fe448a7d20aa67b2aa466d5f2faf131c>`__

Leads to questions:
➊ How can documentation help to provide and share viewhelpers?
➋ Will Gists stay forever? I mean, as long as Github exists and the owner doesn't delete them.
➌ I you have new insights, you'll update the Gist probably?
➍ Can Gists help in creating a Viewhelper library?
➎ Can Gists help in creating a snippet collection?




Tools // Server // Installation
===============================

-  Make sure the Javascript list of available extension manuals is correct

   * https://docs.typo3.org/typo3cms/extensions/
   * https://docs.typo3.org/typo3cms/extensions/extensions.js

-  Elastic Search


Cronjobs
--------

-  Add a cronjob that removes the :file:`/tmp/TCT/RenderDocumentation/lockfile.json` if the
   `RenderDocumentation` job had failed to do so. Otherwise it would take **x** seconds for the
   lockfile to become outdated. Currently **x** is set to 3.600 seconds. That means, that in
   case the buildjob dies with an unhandled exception it will take an hour until **any**
   manual will be rendered again.

Missing features
----------------

#. :file:`Ajaxdownloads.php`: this `$knownpath` isn't correctly handled:
   :file:`/typo3cms/drafts/github/*/`. Wildcards aren't handled yet.




Unicode
=======

See http://unicode-suche.de/unicode-namesearch.pl?term=negative

.. code-block: none

   ➊➋➌➍➎➏➐➑➒➓
   U+2776   ➊ 	1 	e2 9e 8a 	DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT ONE 	INVERSE CIRCLED SANS-SERIF DIGIT ONE
   U+278B 	➋ 	2 	e2 9e 8b 	DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT TWO 	INVERSE CIRCLED SANS-SERIF DIGIT TWO
   U+278C 	➌ 	3 	e2 9e 8c 	DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT THREE 	INVERSE CIRCLED SANS-SERIF DIGIT THREE
   U+278D 	➍ 	4 	e2 9e 8d 	DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT FOUR 	INVERSE CIRCLED SANS-SERIF DIGIT FOUR
   U+278E 	➎ 	5 	e2 9e 8e 	DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT FIVE 	INVERSE CIRCLED SANS-SERIF DIGIT FIVE
   U+278F 	➏ 	6 	e2 9e 8f 	DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT SIX 	INVERSE CIRCLED SANS-SERIF DIGIT SIX
   U+2790 	➐ 	7 	e2 9e 90 	DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT SEVEN 	INVERSE CIRCLED SANS-SERIF DIGIT SEVEN
   U+2791 	➑ 	8 	e2 9e 91 	DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT EIGHT 	INVERSE CIRCLED SANS-SERIF DIGIT EIGHT
   U+2792 	➒ 	9 	e2 9e 92 	DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT NINE 	INVERSE CIRCLED SANS-SERIF DIGIT NINE
   U+2793 	➓ 	10 e2 9e 93 	DINGBAT NEGATIVE CIRCLED SANS-SERIF NUMBER TEN 	INVERSE CIRCLED SANS-SERIF NUMBER TEN


t3SphinxThemeRtd
================

See the `issues <https://github.com/TYPO3-Documentation/t3SphinxThemeRtd/issues>`__!
Just to list some here:

-  Make headlines better distinguishable (`Tweet <https://twitter.com/marantern/status/798133431314026496>`__)


Connect Teams
=============

-  `Calendar "TYPO3 Sprints" at typo3.org <https://typo3.org/events/typo3-sprints/>`__

StackOverflow
=============

See https://github.com/T3DocumentationStarter/Public-Info-009/


Understanding ...
=================

- cHash
- optionSplit
- TYPO3 caching
- typolink
- ...



More to be done
===============

Teach theme tricks
------------------

-  Tell people about css class `compactlist`

Integrate further topics
------------------------

1. `rst-ing with PHPStorm
   <https://docs.typo3.org/typo3cms/drafts/github/wmdbsystems/RSTingWithPhpStormGuide/>`__
   
   That content needs to partly go into `How To Document TYPO3 Projects
   <https://docs.typo3.org/typo3cms/HowToDocument/>`__ and partly into 
   `Documentation Rendering <https://docs.typo3.org/typo3cms/RenderTYPO3DocumentationGuide/>`__.
   
   This should als cover the information of `Sphinx-Doc Installation Steps (2015) 
   <http://mbless.de/blog/2015/01/26/sphinx-doc-installation-steps.html>`__.
   
   Keep an eye on the section about the :file:`_make` folder. 
   Provide a suitable :file:`make`-folder somewhere.




More to be done
===============

-  Tell people about css class `compactlist`


More to be done
===============

.. toctree::

   ToBeDone-2016-11-18.rst


