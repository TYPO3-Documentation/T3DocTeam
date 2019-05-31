.. include:: ../Includes.txt


.. _overview-of-manuals:
.. _overview-of-manuals-review:

=============
Review Status
=============

.. important::

   Information about maintainers was moved to :ref:`overview-of-manuals-maintainer`.

The information in the columns is relevant for reviewing (proofreading,
correcting) the information.

* **State**: Is it up to date? Does it need review?
* **In Progress**: Somebody is already doing something
* **Next step**: to be done next


Review Status of Main Manuals
=============================

In need of general decision:

* :ref:`t3extbasebook:start`: Clarify license, check for overlap with book by Michael Schams,
  make general decision if this should be maintained long term.
* :ref:`t3extbase:start`: Decide on structure. What should be in this guide? Does it cover the
  basics? Currently, it is
* :ref:`t3l10n:start`: Should information in that manual be kept separate?
* ...

In need of branching out for new versions:

* :ref:`t3sitepackage:start`
* :ref:`t3l10n:start`
* :ref:`t3editors:start`
* ...



.. t3-field-list-table::
 :header-rows: 1

 - :Manual:       Manual
   :State:        State
   :InProgress:   In progress
   :NextStep:     Next Step

 - :Manual:       :ref:`t3l10n:start`
   :State:        **outdated** Current "latest" is for version 7.6
   :InProgress:
   :NextStep:     Decision: Should this manual be kept as separate manual or for example be merged to "TYPO3 Explained"?

 - :Manual:       :ref:`t3install:start`
   :State:        **good** Generally, "latest" (9.5) version looks good and up-to-date.
   :InProgress:
   :NextStep:

 - :Manual:       :ref:`t3sitepackage:start`
   :State:        "master" is for TYPO3 8.7
   :InProgress:
   :NextStep:     Check if changes for 9 are necessary, branch out and create changes for 9 

 - :Manual:       :ref:`t3contribute:start`
   :State:        **good** Up-to-date, proofread (4/2018)
   :InProgress:
   :NextStep:

 - :Manual:       :ref:`t3extbasebook:start`
   :State:        **needs revision** Was often mentioned, that it is not up-to-date. Was also mentioned,
                  that language needs improvement.
   :InProgress:
   :NextStep:     Decisions: Clarify license.
                  Decide if all branches should be maintained longterm or only "latest". Possibly,
                  remove other branches from being rendered (branches can be kept but will not
                  be rendered). Review for: up-to-date, proofread language.

 - :Manual:       :ref:`t3extbase:start`
   :State:        **needs revision** Scope of Guide unclear.
   :InProgress:
   :NextStep:     Make decision about guide. Should we continue maintaining it? What is scope?
                  How should it be structured? Should Fluid section be separated?

 - :Manual:       :ref:`t3start:start`
   :State:        9.5 branch fully updated, other branches: unclear
   :InProgress:
   :NextStep:     Remove 8 branch from rendering until updated. Check 8 and 7 branch.

 - :Manual:       :ref:`t3editors:start`
   :State:        Current latest for TYPO3 8
   :InProgress:
   :NextStep:     Branch out and update "latest" for 8 

 - :Manual:       :ref:`t3ts45:start`
   :State:
   :InProgress:
   :NextStep:

 - :Manual:       :ref:`t3templating:start`
   :State:
   :InProgress:
   :NextStep:     

 - :Manual:       `Core ChangeLog <https://docs.typo3.org/typo3cms/extensions/core/latest/>`__
   :State:        **good** Up to date
   :InProgress:
   :NextStep:

 - :Manual:       :ref:`Core API <t3coreapi:start>`
   :State:        Mostly in good shape. Some parts outdated. Some parts missing.
   :InProgress:
   :NextStep:     Check entire manual, if up-to-date for TYPO3 9 (latest)

 - :Manual:       :ref:`t3tca:start`
   :State:
   :InProgress:
   :NextStep:

 - :Manual:       :ref:`t3tsconfig:start`
   :State:
   :InProgress:
   :NextStep:

 - :Manual:       :ref:`t3tsref:start`
   :State:
   :InProgress:
   :NextStep:


.. _overview-of-manuals-review-sysext:

Review Status of System Extensions
==================================

.. t3-field-list-table::
 :header-rows: 1

 - :Manual:       Manual
   :State:        State
   :InProgress:   In progress
   :NextStep:     Next Step

 - :Manual:       `felogin <https://docs.typo3.org/c/typo3/cms-felogin/master/en-us/>`__
   :State:
   :InProgress:
   :NextStep:

 - :Manual:       `fluid_styled_content <https://docs.typo3.org/typo3cms/extensions/fluid_styled_content/>`__
   :State:
   :InProgress:
   :NextStep:

 - :Manual:       `form <https://docs.typo3.org/typo3cms/extensions/form/>`__
   :State:        Up-to-date (assessed after superficially glimpsing through - May, 2019)
   :InProgress:
   :NextStep:

 - :Manual:       `indexed_search <https://docs.typo3.org/typo3cms/extensions/indexed_search/>`__
   :State:
   :InProgress:
   :NextStep:

 - :Manual:       `linkvalidator <https://docs.typo3.org/typo3cms/extensions/linkvalidator/>`__
   :State:
   :InProgress:
   :NextStep:

 - :Manual:       `recycler <https://docs.typo3.org/typo3cms/extensions/recycler/>`__
   :State:
   :InProgress:
   :NextStep:

 - :Manual:       `rte_ckeditor <https://docs.typo3.org/typo3cms/extensions/recycler/>`__
   :State:        Up-to-date (as it was recently published, we assume it is still up-to-date - May, 2019)
   :InProgress:
   :NextStep:

 - :Manual:       `scheduler <https://docs.typo3.org/typo3cms/extensions/scheduler/>`__
   :State:
   :InProgress:
   :NextStep:

 - :Manual:       `sys_action <https://docs.typo3.org/typo3cms/extensions/sys_action/>`__
   :State:
   :InProgress:
   :NextStep:

 - :Manual:       `taskcenter <https://docs.typo3.org/typo3cms/extensions/taskcenter/>`__
   :State:
   :InProgress:
   :NextStep:

 - :Manual:       `workspaces <https://docs.typo3.org/typo3cms/extensions/workspaces/>`__
   :State:
   :InProgress:
   :NextStep:




* rsaauth (rsaauth is outdated!)


.. _overview-of-manuals-review-doc-team:

Writing Documentation and DocTeam (for Review)
==============================================

This is an overview of information About writing documentation and
the documentation team.

The information in the columns is relevant for reviewing (proofreading,
correcting) the information.


.. important::

   We do not list all sources here at the moment.
   For more see :ref:`list-of-manuals-about-writing-docs-about`.

.. t3-field-list-table::
 :header-rows: 1

 - :Manual:       Manual
   :State:        State
   :InProgress:   In progress
   :NextStep:     Next Step

 - :Manual:       :ref:`rendert3docs:start`
   :State:        **needs revision** "Work in progress!"
   :InProgress:
   :NextStep:     Should be updated and "WIP" removed. What is scope of guide? What
                  information should go in "Rendering Guide", what in "Writing Documentation":
                  :ref:`h2document:rendering-docs` and what in
                  `Readme on GitHub for Docker image <https://github.com/t3docs/docker-render-documentation/blob/master/README.rst>`__

 - :Manual:       :ref:`start` (this manual)
   :State:        **In progress**
   :InProgress:
   :NextStep:

 - :Manual:       :ref:`h2document:start`
   :State:        **good** Fully revised, up-to-date! (May 2019)
   :InProgress:
   :NextStep:

 - :Manual:       Team page on **typo3.org**: https://typo3.org/community/teams/documentation/
   :State:        **good** Fully revised, up-to-date! (May 29, 2019)
   :InProgress:
   :NextStep:


 - :Manual:       "About TYPO3 Documentation" on "glue pages" https://docs.typo3.org/About.html
   :State:        **good** Fully revised, up-to-date! (May, 2019)
   :InProgress:
   :NextStep:

 - :Manual:       "Tips" on "start page" https://docs.typo3.org/
   :State:        **good** Fully revised, up-to-date! (May, 2019)
   :InProgress:
   :NextStep:

 - :Manual:       Forge Wiki: https://forge.typo3.org/projects/team-docteam
   :State:        **good** Fully revised, up-to-date! (May, 2019)
   :InProgress:
   :NextStep:
