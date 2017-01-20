.. Tip - just do it:
      don't use TABs (= \t, tabulators)
      replace each TAB by *three blanks* (enable RegExp for Search and Replace in your IDE)
      set TAB width and indentation to THREE in your IDE
      set 'Use blanks instead of TABs' in your IDE


.. With the following include we import some definition. We do this in each and every file.
   so we can change the definition at a single place. Use the relative path to the Includes.txt file,
   which may look as well like ../../../Includes.txt for a deeply nested source file.

.. include:: Includes.txt


.. Usually we define 'php' as default highlight language in Includes.txt.
   With the following 'highlight' directive we switch to reStructuredText as default highlight language.

.. highlight:: rst


.. The following, first section (= headline) is the 'Document Title'.


======================
My Public Info Project
======================


.. The following is 'field list' which is rendered as a horizontal table.
   Think of it as key-value pairs.


:Writing here:    `My Name <my.name@gmail.com>`__
:Rendered:        |today|
:Buildinfo:       `buildinfo <_buildinfo>`_
:Others:          `Who else has a starter project?`__

__ https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-001/TeachingDocs/StarterManuals/

.. _Martin: martin.bless@mbless.de

.. attention::

   Whenever you change something and you want to see the new rendering:
   Don't forget to REFRESH YOU BROWSER. Or, even better:
   Clear the browser cache!



---------------------------------------------

| You like English? Read "Hello_" on this page.
| You like German? Lies "Hallo_" auf dieser Seite.

---------------------------------------------


.. _hello:

**Hello,**

Martin_ here.

What's it about?

#. This is your personal TYPO3 documentation starter project.
   Do with it what you like. Write a note, delete the subfolders,
   create new subfolders, mess it all up: That's ok.

#. Only you and me have write access.

#. Never before has it been easier to write in this format:

   - Goto `the drafts <https://docs.typo3.org/typo3cms/drafts/>`__,
     from there to `the starter projects <https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/>`__
     and from there to YOUR project. Just remember the number. We also keep a list of `"Who is where?" here
     <https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-001/TeachingDocs/StarterManuals/Index.html#who-is-where>`__.
     
   - Go to your "Hello world!" page - for example.
   
   - Press "Edit me on Github". You need to be signed in into Github 
     in your browser and make sure that you have accepted the invitation 
     that Github has sent to you by mail. You can find the invitation in your
     Github account as well.
     
   - You'll be taken to the edit form right away. Write a word, press "Save".
     This creates a commit, and our `docs server is automatically notified that
     there is something new to do.`__
     
   - Wait one, two or three minutes. The cronjob is eager to work every minute.
     **Reload** your browser and **clear** your browser cache.
     
     .. note::
     
        No fork required, no pull request, no commit message, no installation
        required. See, update, save. That's all. And wait a little moment - 
        that's probably the hardest part. Although it's only a short time.
        
   - Oh yes, reST (reStructuredText__) is picky at parts. On the other hand
     it has semantic markup, cares about maximal readability of the source
     you write and is capable of doing things that others can only dream of.
     
   - If something isn't working as you expect:
     
     .. tip:: 
     
        **Watch the log!**
     
        Each documentation project that's rendered by the new tool chain
        leaves a `/_buildinfo` folder that you can inspect in the web.
        The file :file:`warnings.txt` in there is of special interest,
        as it contains the Sphinx_ warnings and error messages.
        
     So you can append `/_buildinfo/` to the root url of your project.
     Or, to make your life easier, add a link like this to your text:
     ```buildinfo <_buildinfo>`__`` It should show up and work like this: 
     `buildinfo <_buildinfo>`__
     
   - I've added the chapters (=subfolder) :doc:`Hyperlinks </Hyperlinks/Index>` and
     :doc:`reStructuredText </reStructuredText/Index>` just to give you some help.
     You can of course delete or rename them as you like.
     
If more comes into my mind I'll add that to the `master template of this starter project`__.
Drop by as you like.

To get a more concrete idea of what you can do with this starter project look at
my starter project. Everything is that easy and inviting that I'm using it myself
as a place to take notes. **Tip:** `Visit Martin's starter project for inspiration!
<https://github.com/T3DocumentationStarter/Public-Info-001>`__

And, **tip!**, watch `the growing list of documentation heros!
<https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-001/TeachingDocs/StarterManuals/Index.html>`__

Have fun, have success, and please: Spread the news about starter projects. We need
many community member that dare to press "Edit me on Github" when they see a mistake
in TYPO3 documentation.

TYPO3 - Inspire people to share!

Martin_


.. These are anonymous hyperlinks. Each link in the text, which is formed by TWO trailing
   underscores, will consume the next of the following links.

__ https://docs.typo3.org/typo3cms/RenderTYPO3DocumentationGuide/ProjectsOnGithub/Index.html
__ https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-000/reStructuredText/Index.html
__ https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-000/


---------------------------------------------


.. _hallo:

**Hallo,**

Martin_ hier.

Worum geht's?

#. Dies ist dein persönliches TYPO3-Documentation-Starter-Project.
   Mach damit was du willst. Schreib eine Notiz, lösch die Unterordner,
   leg andere Unterordner an, mach alles kaputt: Das ist in Ordnung.

#. Nur Du und ich haben Schreibzugriff.

#. Niemals zuvor war es einfacher, in diesem Format etwas zu schreiben:

   - Du gehst auf die `Website <https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/>`__
     und dort zu DEINEM Projekt. Merk dir halt die Nummer.
     
   - Geh zum `Entwurfsbereich  <https://docs.typo3.org/typo3cms/drafts/>`__,
     von dort zu `den Starterprojecten <https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/>`__
     und von dort zu DEINEM Projekt. Merk dir einfach die Nummer. 
     Wir führen auch eine Liste `"Wer ist wo?" hier
     <https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-001/TeachingDocs/StarterManuals/Index.html#who-is-where>`__.
     
   - Geh z. B. auf die "Hello world!" Seite.
   
   - Drücke "Edit me on Github". Auf Github muss du angemeldet sein und darauf achten, dass du die
     Einladung zur Mitarbeit an diesem Repository auch angenommen hast.
     
   - Dann kommst du sofort zum Editierformular. Schreibe ein Wort und drücke "Save". Dadurch `wird
     gleichzeitig der Docs-Server informiert.`__
     
   - Warte ein, zwei oder drei Minuten. Der Cronjob interessiert sich jede Minute dafür, ob er etwas
     für dich tun kann. Dann mach einen Reload im Browser.
     
     .. note::
     
        Kein Fork, kein Pull Request, keine Commit-Message, keinerlei Installation
        erforderlich! Sehen, ändern, speichern. Und warten - das ist bestimmt das Schwerste.
        Aber nur ganz kurze Zeit.
        
   - Ja, das reST-Format (reStructuredText__) ist 
     schon ganz schön pingelig. Dafür arbeitet es aber auch sematisch, gestaltet den
     Quelltext optimal lesbar und kann Dinge, von denen man sonst nur träumen kann.
     
   - Wenn etwas nicht so funktioniert wie erwartet:
     
     .. tip:: 
     
        **Schau ins Protokoll!**

        Jedes Doku-Projekt, dass mit der neuen TYPO3-Documentation_Toolchain gerendert wird,
        erhält auch einen `/_buildinfo` Ordner, den man hier im Web aufrufen kann. Darin ist
        ganz besonders die Datei :file:`warnings.txt` von Interesse, denn sie enthält die
        Sphinx_ Warnungen und Fehlermeldungen.
        
     Hänge also in der Adresszeile des Browsers an die Start-URL deines Projektes ein
     `/_buildinfo/`. Oder füge direkt in deine Doku, zumindest für die Entwicklungszeit,
     einen Link ein: ```buildinfo <_buildinfo>`__`` Der sollte dann so funktionieren: 
     `buildinfo <_buildinfo>`__
     
   - Die Kapitel (=Unterordner) :doc:`Hyperlinks </Hyperlinks/Index>` und
     :doc:`reStructuredText </reStructuredText/Index>` sollen Hilfestellung beim Einstieg
     sein. Sie können natürlich bedenkenlos gelöscht werden.
     
Wenn mir mehr einfällt oder Fragen auftauchen schreibe ich mehr in der
`Mastervorlage des Starter-Projektes`__. Dort kann man also bei Bedarf
reinschauen.

Für Anregungen, was man mit diesem Starter Projekt machen kann, schau
dir meins an. Das Arbeiten damit ist so einfach und einladend,
dass ich es selbst ständig benutze. **Tipp:** `Guck dir zur Anregung mal 
Martin's Starterprojekt an!
<https://github.com/T3DocumentationStarter/Public-Info-001>`__

Und, **Tipp!**, beobachte `die wachsende Liste der Dokumentations-Helden!
<https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-001/TeachingDocs/StarterManuals/Index.html>`__

Viel Spaß, viel Erfolg, und bitte: Weitersagen! Wir benötigen möglichst viele Mitstreiter
in der Community, die sich trauen, "Edit me on Github" zu drücken, wenn sie in der Doku
einen Fehler entdecken.

TYPO3 - Inspire people to share!

Martin_

        
        

.. _Sphinx: http://www.sphinx-doc.org/

.. Dies sind anonyme Hyperlinks. Jeder Link im Text, der durch ZWEI anhängende Unterstriche
   gebildet wird, verbraucht den nächsten aus dieser Liste.

__ https://docs.typo3.org/typo3cms/RenderTYPO3DocumentationGuide/ProjectsOnGithub/Index.html
__ https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-000/reStructuredText/Index.html
__ https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-000/



.. toctree::
   :hidden:

   HelloWorld/Index
   Hyperlinks/Index
   reStructuredText/Index

