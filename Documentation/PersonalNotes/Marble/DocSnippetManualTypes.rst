.. include:: ../../Includes.txt

============
Manual Types
============

Martin Bless [11:34 PM] Slack 2018-01-16

@mathias.schreiber wants to have meta tags in the docs for the indexer of the global search. Example::

   <meta name="book-name" content="blog">
   <meta name="book-version" content="8.7.0">
   <meta name="book-type" content="Extension Manual">

That brings up the question what names we want to agree on for the "book-type".
What about these names (first column is important):

=================  =============================================
BOOK_TYPE          DESCRIPTION
=================  =============================================
Blogpost           Blogpost, opinion, I case we have that somewhen.
Book               Is a book or part of a book
Cheat Sheet        Summarized help notes about various topics.
Extension Manual   Manual of a TYPO3 CMS extension.
Guide              In-depth exploration of specific topics.
Prototype Manual   Structure and markup example for official manuals and extension manuals.
Reference Manual   Exhaustive listings of properties, options, APIs, etc.
Snippet            For snippets, tips, howtos. A howto is much shorter than a tutorial.
Team Notes
Tutorial           Introductory manual into the world of TYPO3 CMS.
=================  =============================================
