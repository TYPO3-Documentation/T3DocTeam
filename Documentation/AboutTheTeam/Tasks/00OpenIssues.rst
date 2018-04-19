.. include:: ../../Includes.txt

==============
List of Issues
==============

Open issues
===========

#. ...

#. The :file:`Includes.txt` file should be updated everywhere
   to have the textroles 'sep' and 'aspect' as well. Note that the
   TypoScript references have 'highlight:: typoscript' as default
   (filed 2018-04-15)::
   
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

   *Keeping track of what we have already:* The :file:`_make` folder should be
   absent and be mentioned in the .gitignore. The other files should be present
   and be ok. The check mark signals what has been checked already and is ok.
   
   ::
   
      =============== ========= ============= =========== ============== =======
      manual          branch    Includes.txt  .gitignore  .editorconfig  _make
      =============== ========= ============= =========== ============== =======
      TCA-Reference   8-7             ✔            ?             ?          ?  
      TCA-Reference   latest          ✔            ?             ?          ?  
      ...
      
      
      
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
   
   - Apply the `"dl-parameters"
     <https://docs.typo3.org/typo3cms/HowToDocument/WritingReST/DefinitionLists.html#list-style-dl-parameters>`__
     style



Resolved issues
===============

(move done issues here)
