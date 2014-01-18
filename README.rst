=======================
Rust tutorial in French
=======================

Homepage for the "Tutoriel Rust en Français", the translation of the official Rust Tutorial in French.

This project holds the source code of the documentation publically available at the following URL:


   http://www.great-a-blog.co/tutoriel-rust/


How to edit documentation ?
===========================

Simply:

- fork this project (https://github.com/Stibbons/rust-tutorial-french)
- edit your changes
- submit to me a Pullrequest (https://help.github.com/articles/creating-a-pull-request)

That's all. Once accepted, the official documentation will be automatically updated.


How is it done?
===============

This github project is linked to the Read my Doc service, which triggers a rebuild of the online
documentation when changes are merged.

A travis build is also triggered (I prefere the notification from travis-ci).

Used online services
--------------------

- GitHub: https://github.com/Stibbons/rust-tutorial-french/
- Read the Docs: https://readthedocs.org/projects/rust-tutorial-french/
- Travis-CI: https://travis-ci.org/Stibbons/rust-tutorial-french


Which tool to edit reStructuredText ?
=====================================

I'm mainly use Sublime Text 3 as my main editor and its quite usefull reStructuredText plugin

- Sublime Text 3: http://www.sublimetext.com/
- reStructuredText plugin: https://github.com/dbousamra/sublime-rst-completion

How to build ?
==============

- I've added the bash script and batch files to support Linux, Mac OS (with homebrew) and Windows compilations.
- You need Python and sphinx to build it. Install it along with the "pip" installer
- With pip, install sphinx with ``pip install sphinx`` (on windows you need to download the official installer)
- The easiest is to use the ``requirements.txt`` file: ``pip install -r requirements.txt``
- On windows you need msysw to have the unix tools like ``bash``, ``make``...


References for this documentation
=================================

- http://stackoverflow.com/questions/315911/git-for-beginners-the-definitive-practical-guide
