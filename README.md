ILIAS Flashcards Training plugin
================================

Copyright (c) 2017 Institut fuer Lern-Innovation, Friedrich-Alexander-Universitaet Erlangen-Nuernberg, GPLv2, see LICENSE

- Author:   Fred Neumann <fred.neumann@ili.fau.de>
- Forum: http://www.ilias.de/docu/goto_docu_frm_3474_1945.html
- Bug Reports: http://www.ilias.de/mantis (Choose project "ILIAS plugins" and filter by category "Flashcards")

Installation
------------
When you download the Plugin as ZIP file from GitHub, please rename the extracted directory to *Flashcards*
(remove the branch suffix, e.g. -master).

1. Copy the Flashcards directory to your ILIAS installation at the followin path (create subdirectories, if neccessary):
Customizing/global/plugins/Services/Repository/RepositoryObject/
2. Go to Administration > Plugins
3. Click "Install" for the Flashcards plugin
4. Click "Activate" for the Flashcards plugin

There is nothing to configure for this plugin.

Usage
-----
This plugin provides a training object for glossary contents.
Therefore you should have glossary with contents avaliable in ILIAS. 
The contents are trained as flashcards according to the training scheme of Sebasian Leitner.

As a Lecturer

1. Add a new "Flashcards Training" object in the repository
2. Edit the properties 
3. Select a glossary from the repository
4. Choose the training mode (asking for term, definition or second definition)
5. Set the training online and save the properties
6. Click "Update Cards from Glossary" to fill the training with content

Changes to a term or definition in the glossary will automatically be reflected in the training.
Newly added terms in the glossary will not automatically be added to the training.
Use "Update Cards from Glossary" to add them.

As a Learner

1. Select the training object in the glossary
2. Click "Fill Startbox" to get the first cards in you start box
3. Click "Start Training" to train these cards
4. For each card look at the front side an try to remember the back side
5. For each card choose whether you remembered it

Train the cards in the startbox daily.

* A known card moves one box forward.
* A difficult card stays in its box.
* An unknown card moves back to the startbox.

Train each box as soon as its capacity is reached. You will see that indicated by an icon.

Version History
===============

* All versions for ILIAS 5.1 and higher are maintained in GitHub: https://github.com/ilifau/Flashcards
* Versions up to 1.3.x are in the 'master' branch
* Version 1.4.x for ILIAS 5.3 is in the 'master-ilias53' branch
* Version 1.5.x for ILIAS 5.4 is in the 'master-ilias54' branch
* Version 1.6.x for ILIAS 6 is in the 'master-ilias6' branch
* Version 1.7.x for ILIAS 7 is in the 'main-ilias7' branch
* Version 1.8.x for ILIAS 8 is in the 'main-ilias8' branch

Version 1.8.0 (2023-12-22)
* Compatibility with ILIAS 8

Version 1.7.1 (2021-09-17)
* Compatibility with ILIAS 7

Version 1.6.0 (2020-09-24)
* Compatibility with ILIAS 6 (thanks to @chsfx)

Version 1.5.1 (2019-10-16)
* Fixed compatibility issue with PHP 7.3 (thanks to Fadi)

Version 1.5.0 (2019-07-15)
* Support for ILIAS 5.4
* Drop support for ILIAS 5.2 and 5.3

Version 1.4.0 (2018-09-19)
* Support for ILIAS 5.3
* Drop support for ILIAS 5.1 and 5.2

Version 1.3.6 (2018-02-07)
* beta support for ILIAS 5.3

Version 1.3.5 (2018-01-31)
* fixed display of "last trained" in ILIAS >= 5.2.10
* adapted mapping of copied terms to ILIAS core (5/2017)

Version 1.3.4 (2017-03-17)
* support for ILIAS 5.2

Version 1.3.3 (2016-03-07)
* support of timings

Version 1.3.2 (2016-02-23)
* stable version for ILIAS 5.1
* fixed ignored offline setting
* improved German language
* added uninstall support
* added "copy permission" (needs to be initialized in permission system)