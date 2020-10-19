.. include:: ../Includes.txt


.. _overview-of-manuals-about:

=====
Scope
=====

This page is used to clarify for the listed manuals and webpages:

What is it about? What is the target group? **What should be documented where?**
What is the scope?

If you are not sure, what to put in which, place: look here.


.. _list-of-manuals-about-writing-docs-about:

Scope of General Manuals
========================


.. todo:: create list of manuals with about information (about, comment)


For now, use `Tutorials and Guides <https://docs.typo3.org/typo3cms/GuidesAndTutorials/Index.html>`__
and `Core Documentation <https://docs.typo3.org/typo3cms/References/Index.html>`__
(References).




.. _list-of-manuals-about-writing-docs-about:

Scope of DocTeam Pages
======================


.. t3-field-list-table::
 :header-rows: 1

 - :Manual:       Manual
   :Scope:        About
   :Comment:      Comment

 - :Manual:       :ref:`h2document:start` (Guide)
   :Scope:        Main documentation for writing documentation on docs.typo3.org,
                  for contributors, extension developers (and Documentation Team).
   :Comment:      Use this as main resource for contributors!


 - :Manual:       :ref:`start` (this manual)
   :Scope:        Information *for* doc team. (In comparison:
   :Comment:      This can be used for things that only concern documentation team. It can
                  also be used for drafts. As information matures, it may get moved either to
                  team page on typo3.org or to "Writing Documentation".


 - :Manual:       Team page on **typo3.org**: https://typo3.org/community/teams/documentation/
   :Scope:        About the "Documentation Team" for interested public. Contains "official,
                  general information". WIP and internal information should be put in :ref:`start`
                  (this manual)
   :Comment:      It's important for interested contributors to find relevant information.
                  Place strategic links on team page about contribution, joining Slack and
                  joining the team. The public should also have the possibility to inform
                  themselves about what team is doing.


 - :Manual:       "About TYPO3 Documentation" on "glue pages" https://docs.typo3.org/About.html
   :Scope:        Contains documentation news, Tips & Tricks ...
   :Comment:      :ref:`h2document:start` now being used as main resource for contributors.
                  In order to not have information in too many different places, the pages
                  "Contribution" and "Writing Documentation" have been replaced by external
                  links to :ref:`h2document:start`.

 - :Manual:       "Tips" on "start page" https://docs.typo3.org/
   :Scope:        **Changed:** Mostly tips about **using** (reading) documentation and
                  **general tips about TYPO3 or where to find things**!
   :Comment:      "Writing Documentation" now being used as main resource for contributors.
                  Because of this, the **tips on writing** documentation have been moved to
                  :ref:`h2document:start` (see startpage).


 - :Manual:       Forge Wiki: https://forge.typo3.org/projects/team-docteam
   :Scope:        This is currently only a placeholder for the
                  `slack call notes <https://forge.typo3.org/projects/team-docteam/wiki/index>`__.
                  Provide miminal information on that page and link elsewhere.
                  Could be removed if we did not still need the slack call notes and other notes.
   :Comment:      todo: move "responsibilities of documentation team" to
                  `team page on typo3.org <https://typo3.org/community/teams/documentation/>`__


 - :Manual:       `docker-render-documentation <https://github.com/t3docs/docker-render-documentation>`__
                  Readme.rst on GitHub
   :Scope:        This is a Github Readme! Explains how to use the official Docker Image for rendering.
   :Comment:

 - :Manual:       `t3SphinxThemeRtd Demo Docs <https://docs.typo3.org/typo3cms/drafts/github/TYPO3-Documentation/t3SphinxThemeRtdDemoDocs/>`__
   :Scope:        Examples of reST rendering. Can be used as testcase for rendering, as showcase of what
                  is possible and as inspiration (as ext:styleguide in core).
   :Comment:

 - :Manual:       `Martin's Starter Project 001 <https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-001>`__
   :Scope:        Various examples, "Teaching Docs", "Style Guides" ...
   :Comment:      Is Martin's manual. Not official. You can read, but not change ...


"What's new?" file archive
   The `documentation subproject "What's new?" at Forge
   <https://forge.typo3.org/projects/documentation-whatsnew>`__
   is used to ① provide a description, to ② list the people involved and,
   most important, to ③ keep a `file archive of all existing PDF files
   <https://forge.typo3.org/projects/documentation-whatsnew/files>`__
   in various languages.

   The slides (pdf files) are advertised on typo3.org with urls pointing
   to their Forge location:

   .. figure:: UsingForge-001.png
      :class: with-shadow
      :width: 62%
