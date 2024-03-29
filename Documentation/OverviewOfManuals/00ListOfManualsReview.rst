.. include:: /Includes.rst.txt


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



.. t3-field-list-table::
 :header-rows: 1

 - :Manual:       Manual
   :State:        State
   :InProgress:   In progress
   :NextStep:     Next Step

 - :Manual:       :doc:`t3l10n:Index`
   :State:        **outdated** Versions 7.6 until master (10) have not been thoroughly reviewed yet.
   :InProgress:
   :NextStep:     Decision: Should probably be merged to "TYPO3 Explained"?

 - :Manual:       :doc:`t3install:Index`
   :State:        **good** Generally, "master" (10) and 9.5 version looks good and up-to-date.
   :InProgress:
   :NextStep:

 - :Manual:       :doc:`t3sitepackage:Index`
   :State:        "master" is for TYPO3 8.7
   :InProgress:
   :NextStep:     Check if changes for 9 and 10 are necessary, branch out and create changes for 9 and 10.

 - :Manual:       :doc:`t3contribute:Index`
   :State:        **good** Up-to-date, proofread (4/2018)
   :InProgress:
   :NextStep:

 - :Manual:       :doc:`t3extbasebook:Index`
   :State:        **needs revision** Was often mentioned, that it is not up-to-date. Was also mentioned,
                  that language needs improvement. Text partially long winded. Could be shortened. Outdated
                  example extensions.
   :InProgress:
   :NextStep:     Decisions: Clarify license.
                  Make general decision. Decide if all branches should be maintained longterm or only "master". Possibly,
                  remove other branches from being rendered or add outdated notice. Review for: up-to-date,
                  proofread language, shorten text, make it better readable.

 - :Manual:       :doc:`t3extbase:Index`
   :State:        **to be deprecated** outdated and incomplete
   :InProgress:
   :NextStep:     Move existing information and add redirects

 - :Manual:       :doc:`t3start:Index`
   :State:        9.5 branch fully updated, master (10) to be updated, other branches: unclear
   :InProgress:
   :NextStep:     No immediate action required.

 - :Manual:       :doc:`t3editors:Index`
   :State:        Current master for TYPO3 8
   :InProgress:
   :NextStep:     Branch out and update "master" for 9 (and 10)

 - :Manual:       :doc:`t3ts45:Index`
   :State:
   :InProgress:
   :NextStep:      Assess quality. Check what is outdated. Is it still helpful in its current form?

 - :Manual:       :doc:`t3templating:Index`
   :State:        todo
   :InProgress:
   :NextStep:     todo

 - :Manual:       `Core ChangeLog <https://docs.typo3.org/typo3cms/extensions/core/latest/>`__
   :State:        **good** Up to date
   :InProgress:
   :NextStep:

 - :Manual:       :doc:`Core API <t3coreapi:Index>`
   :State:        Mostly in good shape. Some parts outdated. Some parts missing.
   :InProgress:
   :NextStep:     Check entire manual, if up-to-date for TYPO3 9 (latest). Add missing information.

 - :Manual:       :doc:`t3tca:Index`
   :State:        unclear
   :InProgress:
   :NextStep:

 - :Manual:       :doc:`t3tsconfig:Index`
   :State:        unclear
   :InProgress:
   :NextStep:

 - :Manual:       :doc:`t3tsref:Index`
   :State:        unclear
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

 - :Manual:       :ref:`start` (this manual)
   :State:        **In progress**
   :InProgress:
   :NextStep:

 - :Manual:       :doc:`h2document:Index`
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
