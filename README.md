AxIssues
========

(c) 2014, Stefan Ebert

Dynamics AX 2012 issue tracker. Intended for usage directly in development or integration system.
Uses internal database for storage. Provides export, import and converting funcionality.

Purpose
=======

Educational project which may, when finished, be useful for direct usage or as base for issue, collaboration or tracking projects.
Uses AX internal database for storage. Provides file based export and import funcionality.

Milestones and goals
====================

MS1 - The basics
----------------

* Build project template.
* Have Enums and EDT present.
* Create all Tables and Relations.

MS2 - First GUI elements
------------------------

* Build main menu and list page.
* Have prototypes for all forms.

MS3 - Controllers and logic
---------------------------

* Implement status statemachine.
* Implement controller for state changes.
* Let new issues be created from issue detail form. Later, this will be replaced by new-dialog.

MS4 - Get things completed
--------------------------

* Replace issue creation by a new-dialog.
* Complete outstanding issues and temporary solutions.
* Complete source code documentation (xml style).
* Ensure all best practise deviations are eliminated.

MS5 - Optimize for usage
------------------------

* Focus on usage and provide easy 1-click steps in UI (ribbons).
* Fine-tune for speed and consider growing data volume.
* Have multi-user usage in mind and therefore, offer reasonable filters and presettings.
* Persist user filters.

MS6 - Deploy
------------

* Provide output in a way simple for others to import and use.
* Have download and install instructions.
* Have AX admin documentation.
* Have AX user documentation.

Environment
===========

IDE used is Microsoft Dynamics AX 2012-R3 IDE.
Programming language is X++.

Tools
=====

To get Dynamics AX elements file-based and suitable for version control, the "AOTExportSeparated" Tool from [Aaron Kunz](https://github.com/DAXaholic) is used, which is located at: https://github.com/DAXaholic/AOTExportSeparated
