Clubplugin
==========

A Drupal integration module for the Onsweb Clubplugin.

For various Dutch sports clubs, Onsweb has developed a plugin that clubs can
use to integrate data about clubs, competitions, standings, recently
played and upcoming games on their website. This module provides an easy way 
to add this jQuery plugin to a [Drupal](http://www.drupal.org) website.


Usage
=====

To use the plugin, you need to sign up for the jQuery plugin through the 
[Onsweb website](http://www.onswebbond.nl/voor-verenigingen/). After signing
up, you'll receive an e-mail with a **download link**, and a **script code**.

Note that a subscription is **not free** and requires a yearly fee to be paid
to Onsweb. The fee allows you to use the data provided through the jQuery
plugin on your website. Usage of this Drupal plugin, that only allows for easy
integration of the jQuery plugin above, **is free**.


Install
=======

To install, follow the steps below.

1. Follow the **download link**, unpack and place the downloaded files in the 
   `libraries/clubplugin` directory on your Drupal install.
2. Install this module and its dependencies.
3. Enable the modules.
4. Use **Settings->jQuery Update** to change the jQuery version to 1.7.
5. Enter the **script code** you received by e-mail in **Settings->Clubplugin**.
6. This page will also indicate whether you placed the downloaded files 
   (from step 1) at the correct location. 
7. Use **Structure->Blocks** to place the 'Clubplugin' block on one or more 
   nodes of your website.
8. Optionally, adapt the look of the plugin data with some css. See the
   Onsweb documentation provided in the download for details.


Dependencies
============

The plugin needs the following Drupal modules in order to work properly:
- **Libraries API (2.x)**: this module integrates the files from the download
  link into the plugin.
- **jQuery Update**: this module allows you to change the used jQuery version
  within Drupal: 1.7 is needed.


Bugs, issues, questions
=======================

For checking known bugs, reporting new bugs and feature requests, and asking
other questions, feel free to file an issue on the github repository for this 
plugin: https://github.com/whyscream/clubplugin/issues .

Copyright
=========

This plugin is written by [Tom Hendrikx](http://www.tomhendrikx.nl) and 
originally developed for the [KV Keizer Karel website]
(http://kvkeizerkarel.nl/). Copyright belongs to Tom Hendrikx, and
licensed under the BSD 3-clause license. See the LICENSE file for details.

All code provided by Onsweb that is downloaded separately from this plugin,
is owned by Onsweb, and copyright belongs to them.
