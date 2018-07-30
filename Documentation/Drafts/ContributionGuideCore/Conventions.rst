.. include:: Includes.txt
.. highlight:: rst

=======================================
DRAFT: Conventions
=======================================

This may or may not be added to the contribution guide.

TYPO3 (core) contribution guide:

Conventions
===========

@internal / @api
----------------

* to differentiate between API functions that extensions may use and internal functions that only the core uses:

   * do not use **@api** 
   * use **@internal** for internal functions
   
(July 2018, #typo3-cms-coredev channel, asked by @sybille)   


Open questions
==============

* should @throws be used in Phpdoc? (is used in a number of cases but not completely and consistently)
