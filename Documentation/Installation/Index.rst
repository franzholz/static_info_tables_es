.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: /Includes.rst.txt


Installation
============

The extension is simply installed using the Extension Manager.

When installing for the **very first time**, the database updates are performed **automatically**. When **re-installing** after an uninstall or when **updating**, the update script needs to be run **manually** in the Extension Manager.

**Note:** It is not recommended to change data manually since changes will be lost the next time you run the update script. If you find any data error please report them on https://github.com/franzholz/static_info_tables_es/issues .

Update script
-------------

The update script can be run manually from the Extension Manager using the appropriate icon in the Actions column (see screenshot).

The update script of "Static Info Tables (es)" only imports the Spanish translations. When running the update script of "Static Info Tables", the basic data and all language packs are imported.
Thus, when the "Static Info Tables" was updated it is sufficient to call the Spanish translation update script only once.

.. figure:: /Images/ExtensionManager.png
	:width: 700px
	:alt: Extension Manager view

	Extension Manager with static_info_tables and static_info_tables_es

	In the actions column, the first icon of "Static Info Tables" will show its configuration options (not available for "Static Info Tables (es)"). The second icon will run the update script.
