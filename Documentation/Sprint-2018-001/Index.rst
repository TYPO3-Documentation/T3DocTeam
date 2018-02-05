.. include:: ../Includes.txt

=========================
T3DocTeam Sprint 2018 (1)
=========================

Possible topics
===============

* global search, elasticsearch
* Book meta data: `slack <https://typo3.slack.com/archives/C028JEPJL/p1517655404000017>`__

     | in my world we have something like this:
     | registry of books, each rendering updates the metaData in the registry
     | from that registry we can then build views to guide readers
     | plus the rendering triggers the indexing of the Elasticsearch
     | plus a couple of other neat things like Tweets etc :smile:
     
* About requiring meta data:

     so we have a few options here:
     
     a) Make proper meta data mandatory for indexing - this puts the work onto the extension authors
     b) make *display* of extension docs rely on proper meta data (even more pressure on extension authors)
     c) try to fix missing meta data ourselves (which will give us more searchresults but also lazy ext authors)
     
     (mattes) As I'm a hardliner, I'd opt for b) :slightly_smiling_face:
     
     
