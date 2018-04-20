.. include:: ../../Includes.txt

==============
List of Issues
==============

Open issues
===========

[DECISION] What to do with the Wiki
-----------------------------------

[TODO] Assign tasks
-------------------

Who can do what? 

[TODO] Sort permissions of Github/TYPO3-Documentation
-----------------------------------------------------

who: marble/lolli

[WORKFLOW] How to keep track of which manual needs editing
----------------------------------------------------------

* How do we keep track of which manual with which branch is in what state of progress 
  and needs editorial attention?
* How do we communicate this to potential contributors, for example those at the UXweek?

[DECISION] What to do with Extbase / Fluid book
-----------------------------------------------

* View Helpers?
* Entire book is continuously being questioned, should be revised / taken offline?

[DECISION] Should we display version hints
------------------------------------------

* Should we display "version hints" (e.g. "new in version 8.7", "changed in version 9.2") 
  in docs. Example: TCA Ref? 
* Example in other docs, see 
  https://docs.saltstack.com/en/latest/ref/configuration/minion.html#master-port-syntax

[DECSIION] General structure for all manuals 
--------------------------------------------

* Should all manuals have an introduction, what should go in there? 
* Should the start page have only the Metadata table or for example contain something that looks nice and makes people curious to dive in, for example an embedded video about the topic or an image. 
* Do we want a "What's new" section for pages and things that have been added recently?
 
[TASK] Move / cleanup all public repos
--------------------------------------
 
Existing issues on forge:

* https://forge.typo3.org/projects/team-docteam/issues
* https://forge.typo3.org/projects/typo3cms-doc-core-api/issues
* ...
 
 
* Should all (public) documentation git projects and their (still relevant) open issues be moved from forge to github? 
* if yes, someone has to do this

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

Some of them are missing information about Slack and are still sending people to the mailing-
list where they will sit in the void and wait forever. 

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
