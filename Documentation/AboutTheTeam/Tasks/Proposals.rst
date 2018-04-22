
.. include:: ../../Includes.txt


.. _tasks-proposals:

=========
Proposals
=========

[PROPOSAL] One Person as mentor for each manual
===============================================

We already have this in an informal way with Lolli taking
care of Core API, for example. But, in general it might be
a good idea if we have one person who feels a little
responsible for each manual.

Would require to get more people involved.

[PROPOSAL] Use decisions
========================

Ask in decisions what people want for the manuals.

Start with a very specific question to keep discussion
focused.

.. tasks-proposals-collaborate:

[PROPOSAL] Collaborate with others
==================================

**This proposal is WIP ...**

Currently some of the best and most up-to-date documentation is created
outside of docs.typo3.org in various blogs or in StackOverflow. This
doesn't necessary have to be bad, BUT, is this information easy to find,
do people learning TYPO3 know where to look and more important: what do
they read when?

If you are looking for something specific, you will usually find what
you need (even though you will often find confusing, contradictory
ressources and more solutions than you ever imagined were possible).

When you are starting to learn you don't know enough to look for a
specific thing. You typically need a tutorial.

Some ideas:

* Can we provide incentives for people already writing excellent
  documentation to write more on docs.typo3.org?
* OR: Do we want to link more to these resources from the docs?
* other solutions?


.. _tasks-proposals-startpage:

[PROPOSAL] Create an up-to-date startpage with list of main ressources
======================================================================

**This proposal is WIP ...**

Currently we have:

`Guides and Tutorials <https://docs.typo3.org/typo3cms/GuidesAndTutorials/Index.html>`__

and


`References <https://docs.typo3.org/typo3cms/References/Index.html>`__

Are the things that are listed here up to date and useful?

*If* the current best practice for learning about *some* things *right now*
is to look in the styleguide or in the bootstrap_package or on some blog,
**instead of in docs.typo3.org** and *if* the Extbase / Fluid guide is not
up to date the current overviews on docs.typo3.org is misleading in some
areas.

What can we do about that?

Also, where does "Tell me something about" fit in here? Should it be
completed and linked to more in some places?

First, we need an overview what we actually have and in what state
it is in, see also: :ref:`overview-of-manuals`


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


.. _tasks-proposals-command-shortcuts:

[Proposal] Command shortcuts for docker
=======================================


**New** : The `docker image <https://github.com/t3docs/docker-render-documentation>`__
is very useful and convenient to use. To make it even easier to use, some suggestions:

* Windows support? (does the current method of source'ing the command into
  the shell work on windows? Can we make the method portable?
* more command shortcuts, for example for opening the generated html in
  the browser:
  `xdg-open "file:///$(pwd)/Documentation-GENERATED-temp/typo3cms/drafts/project/0.0.0/Index.html`
* can we put some basic commands (for example the `xdg-open`) into the
  docs repo itself (like TYPO3 does in a Build folder)? General commands should
  be maintained as 1 central repo (e.g. as a submodule).

See also pending review for inspiration:
`"#54959: Add various Composer scripts" <https://review.typo3.org/54959>`__

