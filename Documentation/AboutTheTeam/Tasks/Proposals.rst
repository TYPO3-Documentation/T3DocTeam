
.. include:: ../../Includes.txt


.. _tasks-proposals:

=========
Proposals
=========

Suggestion: If you want to add a new proposal, add 
it in the top and mark it with *new*. 

[PROPOSAL] Think about Maxwidth for main text
=============================================

If a monitor is wide and resolution high, the 
main content is not easily readable because 
the main content uses entire viewport. 

Actually, in this case the docs are more readable
on a smartphone or other device with smaller screen.

I don't think someone should have to adjust their 
browser width.

Possible solutions:

* restrict the width for the main text, as in 
  http://flowframework.readthedocs.io/en/stable/
* Additionally, use the now free space for the 
  notes / hints / important etc. if there is room. 

`VoteForThis: Sybille, ..., you?`

.. _proposals-one-mentor-per-manual:

[PROPOSAL] One person as mentor for each manual
===============================================

We already have this in an informal way with Lolli taking
care of Core API, for example. But, in general it might be
a good idea if we have one person who feels a little
responsible for each manual.

Would require to get more people involved.

`VoteForThis: Sybille, ..., you?`

**WIP**: Word "mentor" is not really fitting, which word 
is better?

.. _tasks-proposals-one-mentor-per-manual:

[PROPOSAL] Add an "About the main contributors section"
=======================================================

Additionally to :ref:`proposals-one-mentor-per-manual`, 
it might be a good idea, to give them 
credit for it, e.g. have a foto and a link to their
homepage on the front page or in the left sidebar. 

This should only be done
if someone has actually substantially contributed 
and will keep the manual up-to-date. 

The intention of this is to pull some of the people who
are currently maintaining excellent blogs into docs.

Side-Effects:

* Your name is in there, you will **make sure** it looks good!
* People who are currently using their blogs as a marketing 
  instrument, get a platform. Hopefully, someone will be
  more interested in contributing to docs!

.. _proposal-markers-for-editorial-state:

[PROPOSAL] Add metadata / markers for editorial state
=====================================================

* Add metadata for the entire manual
* have a marker per page

The markers could be something simple like a comment that is not visible 
but defines the  state of each page, e.g. `{{outdated}}`, this can be
changed when edited, see Markers in Wiki:
  `markers <https://wiki.typo3.org/Help:Contents#Teamwork_and_page_states_-_draft.2C_review.2C_publish.2C_delete.2C_merge.2C_outdated>`__ 

It would be good if the markers have a naming convention so you could
search for them. 

It would be good if tags for the markers are defined, for example

* outdated
* needs review language (spellcheck/grammar/style)
* needs review technical (check if technically correct)
* needs review didactic (is clear and understandable)
* reviewd for (language|technical|didactic) by <editor> on <date>

.. _tasks-proposals-get-feedback-from-community:

[PROPOSAL] Get Feedback from the community
==========================================

Ask in decisions (or somewhere else?) what people want 
for the manuals.

Start with a very specific question to keep discussion
focused.

Side-Effect: We remind them there is documentation for TYPO3
that needs work and (hopefully) get them engaged. 

**WIP:** This needs some more thought, what exactly we need 
to know from the community and what is the best medium to
ask.

.. _tasks-proposals-command-shortcuts:

[Proposal] Command shortcuts for docker
=======================================

Moved to issue for docker github project, because it only concerns that project: https://github.com/t3docs/docker-render-documentation/issues/8

.. _tasks-proposals-startpage:

[PROPOSAL] Encourage Devs to join Docs team
===========================================

There are some technical tasks that are both interesting for developers
and challenging that maybe we could use help with (search engine,
streamline rendering workflow, ...).

Can we use some of these tasks to interest some developers to join the team
or help without becoming a member? That way they will be familiar with docs
and might be more inclined to add to the documentation as well.

To some, just documenting may not sound so interesting. This way, we
find a way to get them interested.


[PROPOSAL] Create an up-to-date startpage with list of main ressources
======================================================================

**This proposal is WIP ...**

Currently we have:

`Guides and Tutorials <https://docs.typo3.org/typo3cms/GuidesAndTutorials/Index.html>`__

and


`References <https://docs.typo3.org/typo3cms/References/Index.html>`__

Are the things that are listed here up to date and useful?

First, we need an overview what we actually have and in what state
it is in, see also: :ref:`overview-of-manuals`

Questions:

* Can we automatically generate this list?
* Can we additionally add a list, grouped by topic (should not be a problem, if list is automatically generated)?





