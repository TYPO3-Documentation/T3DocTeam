.. include:: ../../Includes.txt

==============
List of Issues
==============

used tags:

* `[PROPOSAL]` : describes an idea, that still needs to be refined and needs
  feedback or approval from the team. Because the proposals tend to be longer,
  the descriptions are currently in a seperate file :ref:`tasks-proposals`
* `[DECISION]` : is something that we need to decide on before moving forward.
* `[TODO]`     : are things that can just be done without waiting for approval
  or discussions about if, how and what.
* `[QUESTION]`
* `[INFO]`


Open issues
===========

.. _todos-linking-problems:

[TODO] Create overview of linking problems and find solution
------------------------------------------------------------

Currently there are some problems with linking, if sections are
moved:

* The URLs change (e.g. /Documentation/Introduction.html#section1 >> 
  /Documentation/Introduction/Slack.html#section1). This means
  that search engines and links from other places become 404.
  See also `t3SphinxThemeRtd Issue #74 
  <https://github.com/TYPO3-Documentation/t3SphinxThemeRtd/issues/74>`__
* Selecting a different version will not longer work, because
  the section has moved in the other branch, e.g. see 
  https://docs.typo3.org/typo3cms/CoreApiReference/7.6/CachingFramework/
  and select 8.7. 

**WIP: Possible solutions and work-arounds:**

* see Martin: `Relocator service 
  <https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-054/PersonalNotes/Marble/IdeaRelocatorService.html>`__
* Use singlepage for "permalink" in sections, as described in issue
  `t3SphinxThemeRtd Issue #74 
  <https://github.com/TYPO3-Documentation/t3SphinxThemeRtd/issues/74>`__
* Think twice about restructuring???  


.. _todos-move-cleanup-public-repos-forge:

[IN_PROGRESS] Move / cleanup all public repos
---------------------------------------------

Existing issues on forge:

* https://forge.typo3.org/projects/team-docteam/issues
* https://forge.typo3.org/projects/typo3cms-doc-core-api/issues
* ...

Move (still relevant) open issues to Github to corresponding project.

* `Assignee: Michael Schams (Security Guide)`
* `Assignee: Sybille Peters (CGL, Core API)`


.. _todos-archive-repos-on-github:

[TODO] Archive no longer used Repos on Github
---------------------------------------------

Archiving means the repositories are still there but less visible and read-only.


See https://docs.typo3.org/typo3cms/References/Index.html

* TYPO3CMS-Reference-CodingGuidelines
* TYPO3CMS-Reference-FileAbstractionLayer (edited)
* TYPO3CMS-Reference-Typo3Services (edited)
* TYPO3CMS-Reference-TyposcriptSyntax

These are all moved to Core API.

.. _todos-search-engine:

[INFO] Status of search engine, next steps
------------------------------------------

What will be indexed by search engine?

* Officiaton reST TYPO3 docs on docs.typo3.org
* Extension docs?
* Wiki?
* What's new?

[DECISION] How do we communicate?
---------------------------------

Slack is ideal for some things but not all. Is there a way we can find
solutions for things that are a little more complex to solve and where
we need to focus on one topic and get it clarified?

Specifically: Can we use `decisions <https://decisions.typo3.org/>`__
for Docs related questions?

"This platform is meant for discussions and votings on strategic topics
of greater impact for the **TYPO3 Core Development.**"

Or anything else? Talk? Mailing-List?

.. _todos-overview-of-all-docs:


[TODO] Searchengine
-------------------

Current status? Does this need help? Next steps?

[TODO]: Finish overview of all docs
-----------------------------------

**new**

Here we try to collect a list of docs we already have: things on
docs.typo3.org, in the Wiki, but also in other places.

Then we can decide, what we have, what we need, if manuals should
be merged, new ones created, things moved from the wiki etc.

:ref:`list-of-current-resources`

[DECISION] How to keep track of which manual needs editing
----------------------------------------------------------

* How do we keep track of which manual with which branch is in what state
  of progress and needs editorial attention?
* How do we communicate this to potential contributors, for example those
  at the UXweek?
* should this be done per manual / per branch / per page + branch?  

Possible solutions:

* The wiki has `markers <https://wiki.typo3.org/Help:Contents#Teamwork_and_page_states_-_draft.2C_review.2C_publish.2C_delete.2C_merge.2C_outdated>`__ , 
  eg. `{{outdated}}`. If we do something similiar, should the 
  markers be visible in the rendered version or only in the source

See Proposal: :ref:`proposal-markers-for-editorial-state`

Also see current draft: :ref:`overview-of-manuals-current-status`


[DECISION] What to do with the Wiki
-----------------------------------

Main problems:

* Some of the pages are outdated
* Not enough people currently working on improving it
* Unclear: What should go in the Wiki, what in docs.typo3.org

Possible solutions:

* Migrate to docs.typo3.org. Not easily possible. 
  Currently there are a number 
  of Wiki pages in different languages, not just
  English. These can't just be migrated to docs.typo3.org
* Clarify scope of docs.typo3.org + Wiki 
* If Wiki is kept, should it be indexed by the search engine
  as well?
* Give the layout / design a do-over? Responsive, modern layout


[TODO] Assign tasks
-------------------

Who can do what?

[TODO] Sort permissions of Github/TYPO3-Documentation
-----------------------------------------------------

`Assignees: marble/lolli`


[DECISION] What to do with Extbase / Fluid book
-----------------------------------------------

* View Helpers?
* Entire book is continuously being questioned, should be revised / taken
  offline / replaced with what?

[DECISION] Should we display version hints
------------------------------------------

* Should we display "version hints" (e.g. "new in version 8.7", "changed
  in version 9.2") in docs. Example: TCA Ref?
* Example in other docs, see
  https://docs.saltstack.com/en/latest/ref/configuration/minion.html#master-port-syntax

[DECSIION] General structure for all manuals
--------------------------------------------

* Should all manuals have an introduction, what should go in there?
* Do we want a "What's new" section for pages and things that have
  been added recently?


[TODO] Cleanup Jobs for all manuals
-----------------------------------

There are some jobs which should be done in ALL manuals:


   *Keeping track of what we have already:* The :file:`_make` folder should be
   absent and be mentioned in the .gitignore. The other files should be present
   and be ok. The check mark signals what has been checked already and is ok.

   ::

      =============== ========= ============= =========== ============== =======
      manual          branch    Includes.txt  .gitignore  .editorconfig  _make
      =============== ========= ============= =========== ============== =======
      CoreApi         latest          ✔            ?             ?          ?
      TCA-Reference   8-7             ✔            ?             ?          ?
      TCA-Reference   latest          ✔            ?             ?          ?
      ...


check the :file:`.gitignore` file
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

intersphinx
~~~~~~~~~~~

Use the same shortcuts for the intersphinx mapping in Settings.cfg

Have a similar structure
~~~~~~~~~~~~~~~~~~~~~~~~

* "Introduction" with "Contrib" section
* possibly place for What's new

Feedback / Contrib
~~~~~~~~~~~~~~~~~~

Update the "Feedback" or "Contribution" section in the "Introduction" section.

Some of them are missing information about Slack and are still sending people
to the mailing-list where they will sit in the void and wait forever.

.editorconfig
~~~~~~~~~~~~~

Add a :file:`.editorconfig` file


dl-parameters
~~~~~~~~~~~~~

The TCA reference has a lot of inlcuded files (:file:`*.rst.txt`) that should
be edited to have the 'dl-parameters' style. See `How to document > styled definition lists
<https://docs.typo3.org/typo3cms/HowToDocument/WritingReST/DefinitionLists.html#list-style-dl-parameters>`__

Replace all tabs by three blanks
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


Includes.txt with textroles
~~~~~~~~~~~~~~~~~~~~~~~~~~~

The :file:`Includes.txt` file should be updated everywhere
to have the textroles 'sep' and 'aspect' as well. Note that the
TypoScript references have 'highlight:: typoscript' as default
(filed 2018-04-15)::

      .. This is 'Includes.txt'. It is included at the very top of each and
         every ReST source file in THIS documentation project (= manual).

      .. role:: aspect (emphasis)
      .. role:: html(code)
      .. role:: js(code)
      .. role:: php(code)
      .. role:: sep (strong)
      .. role:: typoscript(code)

      .. role:: ts(typoscript)
         :class: typoscript

      .. default-role:: code
      .. highlight:: php




Resolved issues
===============

(move done issues here)
