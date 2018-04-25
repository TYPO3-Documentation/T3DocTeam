.. include:: ../../Includes.txt

=======================
Idea: Relocator Service
=======================

https://typo3.slack.com/archives/C028JEPJL/p1524638361000229

Robert Wildling [8:39 AM]
Good morning! I just had this experience: I was looking for docu about the caching framework and found a link to the 7.6 version: https://docs.typo3.org/typo3cms/CoreApiReference/7.6/CachingFramework/
I wanted to change to 8.7 by using the switcher at the bottom of the chapter overview, but 8.7 does not list the caching framework as as separate menu, which is confusing at the first moment, because usually switching to the new version would let me expect that I am lead to the same topic. (At least it does so with other topics like, e.g., Bootstrapping).
My question: Would the docu framework allow tweaking such situation by setting links manually? Or is this just not possible?
Mathias responsed in a PM and let me know, that the docu lacks such a feature. So lets hope Google catches up quickly :slightly_smiling_face: (edited)

Sybille Peters [9:30 AM]
@rowild Thanks for pointing it out. I added it to our list of open issues. So, you are saying you searched on Google and then landed on the 7.6 page?
https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-054/AboutTheTeam/Tasks/00OpenIssues.html#todo-create-overview-of-linking-problems-and-find-solution
What you can do: clicking on 8.7 gets you to the startpage, then you type in "caching framework" and search. not ideal, but at least it gets you there.

Martin Bless [9:45 AM]
FYI: The versionswitcher at the lower left tries to move to the some document in the other version. If that doesn't exist it will go to the start of the manual. I have no idea how that could be changed with reasonable efforts. I think the solution will be found in the - already planned - better search possibilities.
One thing that COULD be made with reasonable efforts would be this: As you know we can link symbolically by means of Sphinx "Intersphinx" crossreferencing. We could have a "service page", lets say "jumpto.php" somewhere, which would relocate you to, for example, "t3tsref:stdWrap". That would be the stdWrap page in the TypoScript reference. I would love to see that service, but on my personal priority list it's far from the top.
