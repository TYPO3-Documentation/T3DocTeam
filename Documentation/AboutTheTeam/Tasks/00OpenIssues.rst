.. include:: ../../Includes.txt

==============
List of Issues
==============

Open issues
===========

(file todos here)

#. 2018-04-15 The :file:`Includes.txt` file should be updated everywhere
   to have the textroles 'sep' and 'aspect' as well. Note that the
   TypoScript references have 'highlight:: typoscript' as default::
   
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

   Keeping track of where it is correct already::
   
      - TCA-Reference 8-7   :  is correct
      - TCA-Reference master:  is correct
      
#. There is more we should apply to ALL manuals:

   - fix the :file:`Include.txt` file
   - check the :file:`.gitignore` file
   - add an :file:`.editorconfig` file
  

#. Sort permissions of Github/TYPO3-Documentation (marble/lolli)

#. What people can do:

   - The TCA reference has a lot of inlcuded files (:file:`*.rst.txt`) that should
     be edited to have the 'dl-parameters' style. See `How to document > styled definition lists
     <https://docs.typo3.org/typo3cms/HowToDocument/WritingReST/DefinitionLists.html#list-style-dl-parameters>`__
     
   - Replace all tabs by three blanks
   
   - Apply the `"dl-parameters" style
     <https://docs.typo3.org/typo3cms/HowToDocument/WritingReST/DefinitionLists.html#list-style-dl-parameters>`__



Resolved issues
===============

(move done issues here)
