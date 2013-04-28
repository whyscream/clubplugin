Clubplugin
==========

A Drupal integration module for the Onsweb Clubplugin.

For various Dutch sports clubs, Onsweb has developed a plugin (in jQuery) that clubs can use to integrate data
about clubs, competitions, standings, recently played and upcoming games on their website. This module 
provides an easy to add this plugin to a [Drupal](http://www.drupal.org) website.


Usage
=====

To use the plugin, you need to sign up for the plugin through the [Onsweb website](http://www.onswebbond.nl/voor-verenigingen/).
After signing up, you'll receive an e-mail with a download link, and a script code.


Install
=======

To install, follow the steps below.
1. Follow the download link, and place the downloaded files in the `libraries/clubplugin` directory on your Drupal install
2. Install this Clubplugin module and its dependencies.
3. Enable the modules.
4. Use *Settings->jQuery Update* to change the jQuery version to 1.7.
5. Enter the script code you received by e-mail in *Settings->Clubplugin*.
6. This page will also indicate whether you placed the downloaded files (from step 1) at the correct location. 
6. Use *Structure->Blocks* to place the `Clubplugin` block on one or more nodes of your website.


Dependencies
============

The plugin needs the following Drupal modules in order to work properly:
- Libraries (2.x): this module couples the files from the download link to the plugin.
- jQuery Update: this module allows you to change the used jQuery version within Drupal: 1.7 is needed.


Bugs, issues, questions
=======================
For checking known bugs, reporting new bugs and feature requests, and asking other questions, feel free to file an issue
on the github repository for this plugin: https://github.com/whyscream/clubplugin/issues .
