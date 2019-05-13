:orphan:


.. include:: ../Includes.txt


.. _overview-of-manuals:

===================
Overview of Manuals
===================

.. _overview-of-manuals-current-status:

State of Manuals
================

Initially taken from `guides and tutorials
<https://docs.typo3.org/typo3cms/GuidesAndTutorials/Index.html>`__
and `references <https://docs.typo3.org/typo3cms/References/Index.html>`__.
For pragmatic reasons we don't list individual branches here.

todo:

* add automatically generated ViewHelper reference
* add "Tell me Something About"


.. t3-field-list-table::
 :header-rows: 1

 - :Manual:       Manual
   :Mentor:       Maintainer / Caretaker
   :State:        State
   :NextStep:     Next Step

 - :Manual:       :ref:`t3l10n:start`
   :Mentor:
   :State:        **outdated** Current "latest" is for version 7.6
   :NextStep:     Create branch for 7.6 and update "latest" for TYPO3 9. Also check, if there is overlap with other manuals. Should this manual be merged to "TYPO3 Explained"?

 - :Manual:       :ref:`t3install:start`
   :Mentor:
   :State:        **good** Generally, "latest" (9.5) version looks good and up-to-date.
   :NextStep:

 - :Manual:       :ref:`t3security:start`
   :Mentor:       Michael Schams
   :State:        Merged into TYPO3 Explained
   :NextStep:

 - :Manual:       `Site Package Tutorial <https://docs.typo3.org/typo3cms/SitePackageTutorial/>`__
   :Mentor:       Michael Schams
   :State:        "master" is for TYPO3 8.7 
   :NextStep:     Check if changes for 9 are necessary, branch out and create changes for 9 

 - :Manual:       :ref:`t3contribute:start`
   :Mentor:       Sybille Peters, Josef Glatz
   :State:        **good** Up-to-date, proofread (4/2018)
   :NextStep:

 - :Manual:       :ref:`t3extbasebook:start`
   :Mentor:
   :State:        **needs revision** Was often mentioned, that it is not up-to-date. Was also mentioned, that language needs improvement.
   :NextStep:     Decide if all branches should be maintained longterm or only "latest". Possibly, remove branches. Review for: up-to-date, proofread language.

 - :Manual:       :ref:`t3extbase:start`
   :Mentor:
   :State:        **needs revision** Scope of Guide unclear.
   :NextStep:     Make decision about guide. Should we continue maintaining it? What is scope? How should it be structured? Should Fluid section be separated?

 - :Manual:       :ref:`rendert3docs:start`
   :Mentor:       Martin Bless
   :State:        **needs revision** "Work in progress!"
   :NextStep:     Should be updated and "WIP" removed. What is scope of guide? Clarify, what information should go in "Rendering Guide", what in "Writing Documentation": :ref:`h2document:rendering-docs` and what in `Readme on GitHub for Docker image <https://github.com/t3docs/docker-render-documentation/blob/master/README.rst>`__

 - :Manual:       :ref:`h2document:start`
   :Mentor:       Martin Bless, Sybille Peters
   :State:        **good** Fully revised, is up-to-date!
   :NextStep:

 - :Manual:       :ref:`t3start:start`
   :Mentor:       Sybille Peters
   :State:        9.5 branch fully updated, other branches: unclear
   :NextStep:     check 8 and 7 branch

 - :Manual:       :ref:`t3editors:start`
   :Mentor:
   :State:
   :NextStep:

 - :Manual:       :ref:`t3ts45:start`
   :Mentor:
   :State:        
   :NextStep:

 - :Manual:       :ref:`t3templating:start`
   :Mentor:
   :State:
   :NextStep:     

 - :Manual:       `Core ChangeLog <https://docs.typo3.org/typo3cms/extensions/core/latest/>`__
   :Mentor:       Christian Kuhn
   :State:        **good** Up to date
   :NextStep:

 - :Manual:       :ref:`Core API <t3coreapi:start>`
   :Mentor:       Christian Kuhn
   :State:        Mostly in good shape. Some parts outdated. Some parts missing.
   :NextStep:     Check entire manual, if up-to-date for TYPO3 9 (latest)

 - :Manual:       :ref:`t3tca:start`
   :Mentor:
   :State:
   :NextStep:

 - :Manual:       :ref:`t3tsconfig:start`
   :Mentor:
   :State:
   :NextStep:

 - :Manual:       :ref:`t3tsref:start`
   :Mentor:
   :State:
   :NextStep:


See also list of documentation about documentation:
:ref:`list-of-manuals-about-writing-docs`


.. _list-of-resources-about-resources:

List of Ressources about ressources
===================================

e.g. answers on StackOverflow where people are pointed to documentation.

* `TYPO3 references
  <https://stackoverflow.com/questions/3928662/typo3-references>`__
* `Stackoverflow: Templating tutorial for beginners
  <https://stackoverflow.com/questions/44407852/typo3-v6-2-x-tutorials-for-beginners>`__
* `What are recommended resources for learning extension development
  <https://stackoverflow.com/questions/50024380/what-are-your-recommended-resources-for-learning-extension-development-for-typo3>`__
* `TYPO3 Fluid and Flux tutorial [closed]
  <https://stackoverflow.com/questions/24910318/typo3-fluid-and-flux-tutorial>`__

Use the answers to check:

* What are people recommending and using? Are they recommending
  outdated resources?
* Where are people not finding the information they need?
* Find ideas to optimize docs
* Please add a new answer if the answers are outdated!


Please note that StackOverflow does not really want questions
about books / tutorials etc., so it is not ideal to ask there.
The questions might get closed,
see `This question <https://stackoverflow.com/questions/24910318/typo3-fluid-and-flux-tutorial>`__
