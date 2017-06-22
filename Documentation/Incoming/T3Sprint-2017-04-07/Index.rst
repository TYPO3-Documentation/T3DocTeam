

=============================
Server-Team-Sprint 2017-04-07
=============================


How to install toolchain "RenderDocumentation" locally
======================================================

1. Requirements

   - python --version
   - pip --version
   - virtualenv --help



Requirements.txt
----------------

::

   git clone https://github.com/marble/TCT.git
   cd TCT

   pip install --upgrade click
   pip install --upgrade pyyaml
   python setup.py install
   tct



~/.tctconfig
============

::

   [general]
   temp_home = /home/marble/Repositories/mbnas/mbgit/tct/TEMPROOT_NOT_VERSIONED
   toolchains_home = /home/marble/Repositories/mbnas/mbgit/toolchains

   [RenderDocumentation]
   email_admin = martin.bless@gmail.com
   email_user_cc = martin.bless@typo3.org
   webroot_abspath = /home/marble/htdocs/docs-typo3-org
   email_user_bcc = martin.bless@gmail.com
   buildsettings_builddir_root = /home/marble/Repositories/mbnas/mbgit/tct/BUILDDIR_NOT_VERSIONED
   htaccess_template_show_latest = /home/marble/Repositories/github.com/TYPO3-Documentation/marble/typo3-docs-typo3-org-resources/userroot/scripts/config/_htaccess
   lockfile_name = lockfile.json
   url_of_webroot = http://docs-typo3-org.local
   webroot_part_of_builddir = /home/mbless/public_html
   latex_contrib_typo3_folder = /home/marble/Repositories/github.com/TYPO3-Documentation/latex.typo3
   email_user_send_to_admin_too = 0
   email_user_to = martin.bless@gmail.com
   email_user_do_not_send = 0
   email_user_receivers_exlude_list = ,
   conf_py_masterfile = /home/marble/Repositories/github.com/TYPO3-Documentation/marble/typo3-docs-typo3-org-resources/userroot/scripts/bin/conf-2015-10.py
   repositories_rootfolder = /tmp/T3REPOS
   extensions_rootfolder = /tmp/T3EXTENSIONS
   extensions_builddir_relpath = typo3cms/extensions
   drafts_builddir_relpath = typo3cms/drafts






System Tools
============

::

   build-essential
   bzip2
   curl
   fdupes
   * git
   graphicsmagic
   graphviz
   mercurial
   nano
   * pandoc
   * python
   python-dev
   python-docutils
   python-imaging
   python-mysqldb
   python-uno
   * python-yaml
   * texlive-base
   * texlive-fonts-extra
   * texlive-fonts-recommended
   * texlive-latex-extra
   * texlive-latex-recommended
   tidy
   tree
   * unzip
   wget
   zip
